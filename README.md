# Branch Cleaner

> **⚠️ UNDER CONSTRUCTION**
>
> This project is currently under active development. Features and APIs are subject to change.

Branch Cleaner is a CLI tool written in Go designed to help developers manage and clean up old git branches.

## Features

- **List Old Branches**: Identify branches that haven't been touched in a while.
- **Configurable Rules**: (Planned) Use a configuration file to define filters and rules for branch removal.
    - Filter by age
    - Filter by author
    - Protect specific branches (e.g., `main`, `master`, `develop`)

## Project Structure

This project follows a standard Go project layout:

- `cmd/`: Application entry points.
- `internal/`: Private application and library code.
- `pkg/`: Library code that's ok to use by external applications.
- `configs/`: Configuration file templates or default configs.

## Getting Started

*(Instructions on how to build and run the tool will be added here)*
