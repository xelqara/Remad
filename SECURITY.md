# Security Policy

## Scope

This policy covers security issues in Remad and any future Xelqara AI component that is released from it.

## Reporting

Do not publish credentials, exploit details, private data, or proof-of-concept attacks in a public issue. Report a suspected vulnerability privately to the authorized Xelqara AI security contact once one is established.

Until a dedicated security channel exists, keep the report confidential and record the affected component, impact, reproduction steps, and suggested mitigation in an approved private channel.

## Secrets

Secrets must never be committed. Rotate any credential that may have been exposed, remove it from active systems, and preserve an incident record. Repository history should not be treated as a secure deletion mechanism.

## Release Review

Before deployment, review authentication, authorization, input handling, logging, dependency risk, data retention, model abuse, prompt injection, and privacy exposure.

This policy is a working draft and not formal legal or security advice.
