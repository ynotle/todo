# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Git Workflow

After completing any meaningful unit of work, commit changes locally and push to GitHub:

- Write clean, descriptive commit messages that explain *why* the change was made, not just what changed.
- Commit frequently so progress is never lost — don't batch unrelated changes into a single commit.
- Always push to the `main` branch on GitHub after committing so the remote stays up to date.
- Before starting new work, ensure the working tree is clean (`git status`).

Example commit flow:
```
git add <specific files>
git commit -m "Short summary of what and why"
git push origin main
```
