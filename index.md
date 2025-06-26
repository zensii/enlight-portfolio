# Project Enlight – Financial Stock Analysis Platform

**Live Demo:** [https://app.enlitix.xyz](https://app.enlitix.xyz)  
**Tech Stack:** Django, PostgreSQL, REST API, Celery, Redis, Docker, Proxmox

## Description
Enlight is a full-stack financial analysis web application that enables users to calculate intrinsic stock values using multiple valuation models and live market data.

## Features
- Real-time API integration with fallback logic
- Celery + Redis background tasks for alerts and price monitoring
- JSON endpoints for AJAX-fed dashboards
- Dockerized deployment with automated update script
- PostgreSQL backend managed via Django ORM
- SSL-secured self-hosted deployment

## Screenshots
![Dashboard](images/dashboard.png)
![Valuation View](images/valuation.png)

## Deployment
- Self-hosted on a Proxmox VM
- Docker Compose for service orchestration
- Custom Bash script for pull/rebuild/restart on Git push

## Source Code
Private repo – available upon request
