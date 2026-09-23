# 90-Day Product Owner Coach

A coaching chatbot that helps a brand-new Product Owner navigate their first 90 days in the role — built with [Claude Code](https://claude.com/claude-code) and running on [BoodleBox](https://boodle.ai/).

**Live chatbot:** https://box.boodle.ai/a/@90-DayProductOwnerCoach

## What this is

This repository contains the system instructions for a BoodleBox chatbot, developed as an assignment for a Foundations of AI course in an M.S. Applied AI program. The assignment's purpose was to practice the full workflow of authoring, version-controlling, and iterating on an AI chatbot's instructions using Claude Code and Git/GitHub — then deploying and testing the result in BoodleBox.

The coach itself is built around a real-world Product Owner onboarding scenario: a Product Owner working inside an agile POD (a small, cross-functional delivery team) alongside a Technical Product Owner, Scrum Master, Tech Lead, and Project Manager. All company-specific and proprietary source material used to inform the coach was intentionally generalized into non-identifying language before being included here — see the note at the top of `chatbot_instructions.md`.

## Repository contents

- **`chatbot_instructions.md`** — the full system instructions pasted into BoodleBox's chatbot builder. This is the source of truth; everything else is derived from it.
- **`chatbot_instructions.docx`** *(not tracked in git — see `.gitignore`)* — a Word-formatted export of the instructions, generated locally for convenience when uploading to BoodleBox.
- **`CLAUDE.md`** — standing context for Claude Code describing how to work on this project.

## What the coach covers

- Core responsibilities for the Product Owner, Technical Product Owner, Scrum Master, Tech Lead, and Project Manager roles, and how they differ from one another
- The product lifecycle from initial idea through full rollout, and the partner teams involved at each stage
- Practical templates: writing backlog work items, OKRs (Objectives and Key Results), sprint ceremonies, a biweekly status report, a quarterly value scorecard, and a product roadmap
- Situational frameworks such as RACI, DACI, SBAR, and DMAIC (Lean Six Sigma), and when to reach for each
- Coaching behaviors: a 30-60-90 day pacing framework, building key relationships, running effective 1:1s, and an honest accounting of what the coach can and can't do (e.g., it cannot set real reminders or generate images)

## Branching

- `main` — stable baseline; no work happens directly on this branch.
- `week4-assignment` — the original assignment branch containing the initial chatbot instructions.
- Feature branches (e.g., `feature/address-chatbot-issues`) — used to fix specific issues found while testing the live chatbot in BoodleBox, then merged back in.
