# zaimsides.github.io
---
NaiksLevel Fitness — Privacy Policy
---

# Privacy Policy — NaiksLevel Fitness

**Last updated:** September 1, 2026  
**Developer:** Zaim Zahisham  
**Contact:** [zaimsides@gmail.com](mailto:zaimsides@gmail.com)  
**App:** NaiksLevel Fitness (Android)

This Privacy Policy describes how NaiksLevel Fitness ("the App," "we," "us") handles information when you use our workout tracking application.

---

## Summary

- You can use the **core workout features as a guest** without creating an account. Workout data is stored **locally on your device**.
- **Optional account linking** (Google sign-in or email one-time code) enables **cloud backup and sync** via Supabase.
- **Premium subscriptions** (remove ads, higher AI limits) require a linked account and are processed by **Google Play** and **RevenueCat**.
- The free tier may show **ads** (Google AdMob) and optional **AI features** that send workout-related data to our servers for processing.
- We do **not** sell your personal information.

---

## Information We Collect

### A. Information stored locally (guest mode)

If you use the App without linking an account, we store workout-related data **on your device only**, including for example:

- Workout sessions, sets, reps, weights, durations, and notes  
- Exercises, routines, and muscle groups  
- XP, levels, and gamification progress  

This data is **not** transmitted to our servers unless you link an account and sync, or you use online-only features described below.

### B. Information collected when you link an account

If you choose to link an account, we collect and store:

| Data | Purpose |
|------|---------|
| **Email address** | Account identification, sign-in (email OTP), and communication about your account |
| **User ID** | Unique account identifier (Supabase Auth UUID) for sync and subscription linking |
| **Workout and app data** | Cloud backup and sync across devices (exercises, routines, sessions, sets, XP, groups, premium status flags, AI usage counters) |

**Sign-in methods:** Google OAuth and email one-time password (OTP) via Supabase Auth.

Linking an account is **optional** except when purchasing or restoring Premium.

### C. Subscription and purchase information

If you purchase Premium:

- **Google Play** processes payment. We do **not** receive your full payment card details.
- **RevenueCat** receives subscription status, product identifiers, and an app user ID to manage entitlements (e.g., ad-free access, AI quota tier).
- We store **premium status** and related flags locally and in your cloud user record when synced.

### D. Advertising (free tier)

If you are not Premium, the App uses **Google AdMob**, which may collect:

- Advertising ID (AAID)  
- Device and app interaction data needed to show and measure ads  

See [Google’s Privacy Policy](https://policies.google.com/privacy) for how Google uses this data.

You can limit ad personalization in your **Android Settings → Google → Ads**.

### E. AI features (online only)

Optional AI features (e.g., workout summary, progressive overload analysis, routine generation) require an **internet connection**. When you use them, we send relevant workout context (exercises, sets, notes, session metadata) to **Supabase Edge Functions**, which call **Google Gemini** to generate a response.

- AI API keys are stored **server-side only**, not in the App.
- AI usage may be subject to **monthly quotas** (free, Premium monthly, or Premium yearly tiers).

### F. Information we do not collect

We do **not** intentionally collect:

- Precise location (GPS)  
- Contacts, photos, or microphone recordings  
- Medical records or clinical health data  

The App tracks **fitness activity you enter** (workouts); it is not a medical device.

---

## How We Use Information

We use information to:

- Provide workout logging, XP/leveling, and offline-first functionality  
- Sync your data when you link an account  
- Show ads on the free tier (AdMob)  
- Process Premium subscriptions (Google Play, RevenueCat)  
- Provide optional AI features  
- Enforce AI usage limits and prevent abuse  
- Respond to support and legal requests  

---

## How We Share Information

We share information only with **service providers** that help us operate the App:

| Provider | Role |
|----------|------|
| **Supabase** | Authentication, database, sync, Edge Functions (AI) |
| **Google Play** | In-app purchases and subscriptions |
| **RevenueCat** | Subscription entitlement management |
| **Google AdMob** | Advertising (free tier) |
| **Google (Gemini)** | AI text generation via our Edge Functions |

We do **not** sell your personal information. We may disclose information if required by law or to protect rights and safety.

---

## Data Retention

- **Guest (local-only) data** remains on your device until you clear app storage, uninstall the App, or delete local data.  
- **Cloud data** (linked accounts) is retained while your account is active.  
- After a **deletion request**, we delete or anonymize cloud account data within **30 days**, except where we must retain minimal records for legal, tax, or fraud-prevention purposes (e.g., purchase records via Google Play/RevenueCat under their policies).

---

## Security

Data transmitted between the App and our servers uses **encryption in transit (HTTPS/TLS)**. No method of storage or transmission is 100% secure.

---

## Your Choices

- **Use as guest** — no account required for core workouts.  
- **Link account** — optional, for sync and Premium.  
- **Premium** — removes ads and increases AI limits.  
- **Opt out of personalized ads** — Android system ad settings (ads may still appear).  
- **Delete account and data** — see [Delete your account](#delete-your-account) below.

---

## Children’s Privacy

The App is not directed at children under 13 (or the applicable age in your country). We do not knowingly collect personal information from children. Contact us if you believe a child has provided personal information.

---

## International Users

If you use the App outside your home country, your information may be processed in countries where our service providers operate (including the United States, where Supabase and Google may process data).

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will update the “Last updated” date above. Continued use of the App after changes means you accept the updated policy.

---

## Contact

**Zaim Zahisham**  
Email: [zaimsides@gmail.com](mailto:zaimsides@gmail.com)

For privacy questions, account deletion, or data requests, email us from the address linked to your account when possible.

---

## Delete Your Account {#delete-your-account}

You can request deletion of your **linked account** and **cloud-stored data** associated with NaiksLevel Fitness.

### Option 1 — In the app (recommended)

1. Open **NaiksLevel Fitness**.  
2. Go to **Profile**.  
3. Ensure your account is **linked** (Google or email).  
4. Tap **Delete account** and confirm.  
5. This removes your cloud account and synced workout data from our systems. **Local data on your device** may remain until you clear app storage or uninstall the App.

### Option 2 — Email request (always available)

If you cannot use the App or in-app delete is unavailable:

1. Email **[zaimsides@gmail.com](mailto:zaimsides@gmail.com)** from the **same email address** used to link your account.  
2. Subject line: **NaiksLevel — Delete my account**  
3. Include: the email on your account and a short confirmation that you want all cloud data deleted.  
4. We will verify ownership and delete your Supabase auth account and associated cloud workout data within **30 days**.  
5. We will confirm by email when complete.

### What is deleted

When your linked account is deleted:

- Supabase authentication account  
- Cloud copies of workouts, exercises, routines, groups, XP/progress, and related synced records tied to your user ID  
- Premium flags and AI usage counters in our database (active subscriptions should be **cancelled in Google Play** separately)

### What may be retained

- Information Google Play / RevenueCat must retain for billing, tax, or fraud prevention (under their policies)  
- Aggregated or anonymized data that cannot identify you  
- Data already on your device until you remove it locally  

### Guest users (no linked account)

If you never linked an account, **no cloud account exists** to delete. Remove local data by:

- **Android Settings → Apps → NaiksLevel Fitness → Storage → Clear data**, or  
- Uninstalling the App  

### Cancel subscriptions

Deleting your account does **not** automatically cancel a Google Play subscription. Cancel in:

**Google Play Store → Profile → Payments & subscriptions → Subscriptions → NaiksLevel Fitness**

---

*End of Privacy Policy*
