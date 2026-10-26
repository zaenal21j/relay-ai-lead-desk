# Relay AI Lead Desk

An AI-assisted workspace for capturing inbound leads, organizing requests, and preparing reply drafts for human review.

## Current stage

This repository currently contains an interactive front-end prototype. The leads and integration states are sample data. AI processing, database storage, and external services are not connected yet.

## Planned build

- Laravel and PHP application with a responsive lead dashboard
- Public lead intake endpoint with validation and duplicate protection
- Database-backed lead list, details, statuses, and audit log
- AI-generated lead summaries and reply drafts with human approval required
- Webhook delivery with retry handling and delivery logs
- Google Sheets integration and shared-hosting deployment guide

## Explore the prototype

Open `index.html` in a browser to interact with the dashboard, lead list, editable reply draft, integrations, and settings screens.

## Security principles

- Keep provider API keys on the server.
- Never send replies automatically; require human approval.
- Validate inbound data and process only what is needed.
- Record integration outcomes without exposing secrets.
