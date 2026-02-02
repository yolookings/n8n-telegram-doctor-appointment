# Telegram & Lovable Integration for Doctor Appointment

## Description

This assignment extends an existing n8n workflow by adding two interaction channels:

- Telegram-based chat interaction
- Web-based appointment booking using Lovable

The system is used for **Dr. Strange’s appointment scheduling**, with n8n acting as the backend automation engine.

---

## Task 1: Telegram Integration

- Replaced Chat Trigger with **Telegram Trigger**
- Handled user messages via Telegram Bot
- Sent responses back to users using Telegram Send Message node
- Tested multiple chat scenarios

---

## Task 2: Lovable Frontend & Webhook

- Created a simple appointment booking UI using **Lovable**
- Collected user appointment details via form
- Sent form data to **n8n Webhook (POST)**
- Processed appointment requests in the existing workflow
- Returned confirmation response (optional)

---

## Tools Used

- n8n
- Telegram Bot API
- Lovable
- Webhook

---

## Result

The workflow successfully handles appointment requests from both **Telegram** and **Lovable frontend**, and processes them end-to-end without errors.

---
