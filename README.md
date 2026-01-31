# Workbook 🚀

Workbook is a GitHub-based project designed to integrate GitHub Webhooks with a backend service for automation, deployments, or event handling.

---

## 📌 Features
- GitHub Webhook integration
- Push event handling
- Secure webhook using secret key
- Easy to deploy on any server
- Beginner friendly setup

---

## 🔗 Webhook Setup (GitHub)

Go to your repository:
It should:
- Accept JSON data
- Verify GitHub signature
- Return HTTP 200 response

---

## 📦 Example Payload
GitHub sends data like:
```json
{
  "ref": "refs/heads/main",
  "repository": {
    "name": "workbook"
  },
  "pusher": {
    "name": "username"
  }
}### Requirements
- Accept JSON payload
- Validate GitHub signature
- Respond with HTTP `200 OK`

---

## 📦 Sample Webhook Payload

```json
{
  "ref": "refs/heads/main",
  "repository": {
    "name": "workbook"
  },
  "pusher": {
    "name": "sonukumar"
  }
}
