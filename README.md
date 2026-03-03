# Cleario POC — Clickable Prototype

Interactive prototype for the Cleario PC Optimizer cross-sell flow. Built for stakeholder review of the proposed notification-to-purchase experience.

## Live Demo

**[View Prototype](https://yjiao368.github.io/cleario-poc-prototype/)**

## Screens

1. **Notification** — System tray popup showing SmartScan results (multi-issue example with memory, registry, junk). Includes auto-dismiss countdown, "Remind me later", and "Don't show again" flows.
2. **Your Info** — Step 1 of checkout: name, email, marketing opt-in. No account creation.
3. **Review & Pay** — Step 2: pre-selected plan (1-year, 5 devices), card/PayPal payment, auto-renewal disclosure.
4. **Confirmation** — Step 3: license key with copy button, download CTA, 3-step activation guide, order summary.

## How to Use

Open index.html in any browser. Navigate between screens using the top nav bar, flow pills, or Previous/Next buttons. All interactions are functional (notification countdown, payment tab switching, copy-to-clipboard).

## Context

- **Product:** Cleario PC Optimizer (RealDefense System Mechanic white-label)
- **Target:** Adaware Privacy free users
- **Flow:** SmartScan SDK detects issues > Feature Flag triggers notification > Direct to cart > License key activation
- **Requirements:** See Confluence — Cleario POC Product Requirements (https://avanquestsoftware.atlassian.net/wiki/spaces/AGP/pages/5905186870)

## Status

Prototype is draft — pending stakeholder approval and Figma style alignment. Pricing is placeholder.
