# Dafory Evidence Pack Template

Public evidence pack template for SaaS QA and launch readiness reviews by **Dafory**.

This template is designed to document findings, risks, screenshots, recommendations and launch readiness decisions for demos, SaaS products, landing pages and digital platforms.

It is part of the public Dafory ecosystem and supports services such as **Dafory Demo Doctor** and **Dafory Launch Guard**.

## Purpose

An Evidence Pack helps teams understand:

- What was reviewed
- What works correctly
- What needs improvement
- Which risks should be fixed before launch
- Which issues affect user trust
- What actions should be prioritized
- Whether the product is ready to be presented, sold or launched

## Review summary

| Field | Value |
|---|---|
| Product name | Example SaaS Product |
| Review type | Demo Doctor / Launch Guard |
| Review date | YYYY-MM-DD |
| Reviewer | Dafory |
| Environment | Demo / Staging / Production |
| Device coverage | Mobile / Desktop |
| Final verdict | APPROVED_WITH_WARNINGS |

## Verdict states

Use one of these decision states:

- `APPROVED`: ready to present or launch.
- `APPROVED_WITH_WARNINGS`: usable, but with minor issues.
- `NEEDS_FIXES`: important fixes required before launch.
- `BLOCKED`: critical issue prevents launch.
- `REJECTED`: not ready and needs major rework.

## Finding format

Each finding should include:

```md
### Finding 001: Short title

**Severity:** Low / Medium / High / Critical  
**Category:** UX / UI / Functional / Mobile / Data / Security / Commercial  
**Status:** Open / Fixed / Accepted risk  
**Evidence:** Screenshot, URL, video or description  

**Problem:**  
Describe what is wrong.

**Impact:**  
Explain why it matters.

**Recommendation:**  
Explain what should be fixed or improved.

**Priority:**  
P0 / P1 / P2 / P3
