# responsible-disclosure

Templates and a sanitized portfolio for coordinated vulnerability disclosure. No live or unfixed findings appear here: everything published is either a placeholder, a public report, or a report the maintainer has resolved and approved for release.

## Disclosure policy

1. **Private first.** Report through the program's own channel: its security email, its bug-bounty platform, or a GitHub private vulnerability report where the project accepts one.
2. **Read the program.** Reward tiers, out-of-scope items, required proof, and subject or form rules differ per program. Confirm them before you invest.
3. **Prove it.** A minimal reproduction — a Foundry test on a fork, a `curl` with the request and response, a screenshot of the response. No reproduction, no report.
4. **Rate it honestly.** No High or Critical claim without a proven path to funds, data, or state. A defence-in-depth gap is not a critical.
5. **Give a fix.** Maintainers triage faster when the report names the minimal change.
6. **Respect the embargo.** Nothing public until the maintainer confirms a fix, or the program's disclosure window closes.

## Templates

- `templates/email-report.md` — the email body structure.
- `templates/advisory-body.md` — the longer form for a GitHub advisory or a platform submission.

## Portfolio

Reports are published here only after resolution, and only in sanitized form: target renamed where the program prefers it, repro trimmed to the minimum, and no victim data. The index below is intentionally empty until the first approved publication.

| Report | Target | Class | Status |
|---|---|---|---|
| — | — | — | — |

## Why sanitized

A bug-bounty report often contains enough detail to be re-weaponised. Publishing it before a fix, or publishing another user's data, ends the researcher's relationship with the program. Keep the portfolio useful and safe.
