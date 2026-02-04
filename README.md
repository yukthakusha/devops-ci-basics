# DevOps CI Basics

This project demonstrates a basic Continuous Integration (CI) pipeline using GitHub Actions.

## What this project does
- Automatically runs a workflow whenever code is pushed to the main branch
- Uses GitHub Actions to execute commands on a Linux environment
- Verifies that the CI pipeline is working correctly

## Tools & Technologies
- GitHub
- GitHub Actions
- YAML
- Linux (Ubuntu)

## Workflow Details
The CI workflow:
- Triggers on every push to the `main` branch
- Runs on an Ubuntu virtual machine
- Checks out the repository code
- Executes simple shell commands

## Why this matters
Continuous Integration ensures that code changes are automatically tested or validated, helping teams detect issues early and maintain code quality.

## Author
Yuktha
