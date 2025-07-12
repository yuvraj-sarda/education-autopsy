# Phone Line Workflow: Collecting Insights by Voice

> **Purpose:** Give anyone a friction-free way to share thoughts on education. A simple phone call turns spoken ideas into research insights.

## Why a Phone Line?

• Works from any phone, no apps or internet required.  
• Voice captures nuance that text can miss.  
• Inclusive for people who prefer talking over typing.

## How It Works (High-Level)

1. **Share** – Caller dials a public number and is greeted by a friendly voice that invites them to speak freely about education. We could also ask specific questions we are looking to gather more data on. Could be an ElevenLabs + Twilio setup.
2. **Transcribe** – The conversation is converted to text in real time.  
3. **Anonymize** – Personal identifiers are automatically removed.  
4. **Extract Insights** – An AI agent reads the cleaned transcript, pulls out key themes, and suggests where they belong in the repository. Any conversations aimed at spamming / jailbreaking are ignored.  
5. **Publish** – A summary plus the anonymous transcript are added to a pull request for maintainers to review and merge.

## Safeguards

* Callers hear a consent statement explaining recording and anonymization.  
* Saying “delete my call” at any time cancels the process.  
* Raw audio is deleted after a short retention period; only anonymous text remains.


## Status

Concept drafted — technical implementation will be detailed later. Feedback welcome!
