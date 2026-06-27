# README.md
# Karpathy Official CLAUDE.md Rules
The official internal CLAUDE.md document written by Andrej Karpathy for Claude Code, aiming to standardize LLM code generation behavior and avoid recurring predictable bugs when writing code.

## Source & Disclaimer
This document is transcribed and sorted based on the leaked content shared at:
https://x.com/Raytar/status/2070577723089768500

**Copyright & Infringement Notice**:
All content belongs to the original author Andrej Karpathy. If any copyright holder believes this repository involves infringement, please contact me immediately, and I will delete the entire repository and all related files without delay.

## Background Introduction
Andrej Karpathy joined Anthropic in May 2026. After five weeks of internal practice and debugging with Claude Code, he summarized this complete set of 10-rule CLAUDE.md discipline, which is an upgraded and expanded version of the earlier 4-rule community edition with 180k+ GitHub stars.

Large language models repeatedly produce fixed, predictable defects when generating code, instead of random errors. They can output text that looks logically reasonable, but often fail to match existing project styles, ignore test verification, over-engineer simple requirements, and make blind architectural assumptions without communication.

This set of rules serves as a strict constraint system for Claude Code, turning reckless code-writing AI agents into rigorous engineering collaborators.

## File Description
- `claude.md`: The full original rule document formulated by Andrej Karpathy, containing 10 core mandatory rules for LLM code writing, including pre-reading codebase, demand analysis, minimal code principle, surgical modification, test verification, standardized debugging, dependency management, communication specifications, and common failure mode identification.

## How to Use
1. Copy the `claude.md` file to your claude code.
2. When using Claude Code, the model will automatically read and follow all constraints defined in this file during code generation, refactoring, bug fixing and debugging tasks.
3. The document is written in plain Markdown without redundant escape symbols, fully compatible with native reading logic of Claude Code.

## Core Value
1. Minimize unnecessary code diff changes and avoid random modification of irrelevant code.
2. Eliminate over-engineering and premature abstract design that leads to repeated code rewriting.
3. Enforce demand confirmation and pre-planning before coding to prevent directional deviation.
4. Add complete self-verification and debugging standards to reduce online production bugs.
5. Standardize communication logic between AI and developers to clarify all implicit architectural decisions in advance.

## Repository Info
Repo Name: karpathy-claude-md
Owner: white-sand-grand

## License
This repository only sorts and shares leaked public industry documents for technical learning and communication purposes. All intellectual property rights of the original text belong to Andrej Karpathy. Commercial use of the content is not encouraged. Remove all files immediately upon copyright infringement notification.