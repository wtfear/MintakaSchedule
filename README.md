<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="public/brand/mintaka-banner.svg">
    <source media="(prefers-color-scheme: light)" srcset="public/brand/mintaka-banner.svg">
    <img src="public/brand/mintaka-banner.svg" alt="MintakaSchedule Banner" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://github.com/wtfear/MintakaSchedule/actions/workflows/ci.yml">
    <img src="https://github.com/wtfear/MintakaSchedule/actions/workflows/ci.yml/badge.svg" alt="CI Status">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-emerald.svg" alt="License: MIT">
  </a>
  <a href="https://nextjs.org">
    <img src="https://img.shields.io/badge/Framework-Next.js-black.svg" alt="Next.js">
  </a>
  <a href="https://prisma.io">
    <img src="https://img.shields.io/badge/ORM-Prisma-2D3748.svg" alt="Prisma">
  </a>
  <a href="https://docker.com">
    <img src="https://img.shields.io/badge/Container-Docker%20Compose-2496ED.svg" alt="Docker Compose">
  </a>
</p>

<h1 align="center">MintakaSchedule</h1>

<p align="center">
  <strong>Autonomous Appointment Booking &amp; Scheduling Engine</strong><br>
  <em>Engineered for Healthcare Clinics, Salons, Legal Firms, and Service SMBs by WTFear Agency</em>
</p>

---

## 🏛️ Executive Summary

**MintakaSchedule** is an institutional-grade, 100% MIT-licensed appointment booking and scheduling infrastructure built on **Next.js**, **TypeScript**, **Prisma**, **tRPC**, and **PostgreSQL**.

Unlike proprietary scheduling platforms (Calendly, Acuity, or SimplyBook.me) that charge recurring per-user fees and restrict custom webhook triggers, MintakaSchedule gives agencies complete ownership over client calendar infrastructure. It integrates natively with **`CastorChat`** (for automated WhatsApp booking notifications) and **`ArcturusFlow`** (for calendar-driven CRM automations).

### The Agency Commercial Advantage ($20k – $50k+ Engagements)
* **High SMB Demand:** Clinics, consulting firms, dental practices, and wellness centers require branded booking experiences.
* **Instant WhatsApp Booking Confirmations:** Pairs directly with CastorChat (Meta WhatsApp Cloud API) to send automated reminders and reduce no-shows by up to 60%.
* **Timezone Intelligence:** Automatic daylight saving adjustments and multi-participant scheduling across global timezones.
* **100% Pure MIT Licensing:** Based on the official MIT open-source foundation (`calcom/cal.diy`), completely free of copyleft restrictions.

---

## ⚡ Core Operational Capabilities

```
                       ┌───────────────────────────────┐
                       │     MINTAKA SCHEDULE CORE     │
                       │    (Next.js + Prisma + tRPC)  │
                       └──────────────┬────────────────┘
                                      │
       ┌──────────────────┬───────────┴───────────┬──────────────────┐
       ▼                  ▼                       ▼                  ▼
┌──────────────┐   ┌──────────────┐        ┌──────────────┐   ┌──────────────┐
│ CALENDAR SYNC│   │ TIMEZONE ENG │        │ NOTIFICATION │   │ EMBED WIDGET │
│ • Google Cal │   │ • Auto Detect│        │ • WhatsApp   │   │ • React Pop  │
│ • Outlook    │   │ • DST Aware  │        │ • Email SMTP │   │ • Inline     │
│ • Apple iCal │   │ • Multi-Host │        │ • SMS Hook   │   │ • iFrame     │
└──────────────┘   └──────────────┘        └──────────────┘   └──────────────┘
```

---

## 🚀 Quick Start (Docker Compose)

```bash
# 1. Clone repository
git clone https://github.com/wtfear/MintakaSchedule.git
cd MintakaSchedule

# 2. Configure environment
cp .env.example .env

# 3. Launch stack
docker compose up -d
```

Access the scheduling web app at [http://localhost:3000](http://localhost:3000).

---

## 📜 License

MintakaSchedule is open-source software licensed under the **[MIT License](LICENSE)**.
