# OctoAcme Project Management Docs (README)

This README provides a concise summary of OctoAcme's project management approach and links to the full process documents in this repository's docs/ folder.

Overview

OctoAcme runs projects with a clear, stage-based lifecycle and lightweight artifacts to keep work visible and accountable. Initiation begins with a Project One‑pager that captures the problem, objective, success metrics, stakeholders, and a high-level timeline; once success criteria, stakeholder alignment, and team availability are confirmed, work moves into planning. Planning converts approved initiatives into prioritized backlogs with estimates, a Definition of Done, and a release/milestone map. Execution follows iterative delivery using a project board and small, testable increments.

Workflows emphasize predictability and low friction. The team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a standard PR workflow: include an issue link and acceptance criteria in PR descriptions, run automated tests and linting in CI before requesting review, and require at least one approval before merging. Releases are classified as patch, minor, or major and require pre-release checks (smoke tests, rollback plans, release notes) and staged verification. Risk and dependency management are tracked in a Risk Register and escalated through a defined path when needed.

Roles & Communication

Roles and responsibilities are explicitly defined so ownership is clear: Product Managers own outcomes and prioritization; Project Managers coordinate delivery, schedules, and stakeholder communications; Developers implement features and tests; QA validates acceptance criteria and runs manual or automated checks; stakeholders provide input and approvals. Communication cadence includes daily standups for progress and blockers, weekly delivery syncs for progress and risk review, weekly PM+PdM alignment, and monthly stakeholder updates.

Quality & Assurance

Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA where needed. CI and linting are required before requesting reviews. The project maintains checklists for execution, deployment, and rollback, and stores process update requests via an ISSUE_TEMPLATE to ensure process docs stay current.

Docs index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

Notes

- Keep this README short and update it when process docs change to keep the index accurate.
- Suggested location: docs/README.md (this file).

References issue #1
