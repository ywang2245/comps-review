# PhD Comprehensive Exams Preparation System

> A self-built study companion for surviving the doctoral Leadership Comprehensive Exam — one paper at a time, on whatever device happens to be in your hand.

Built because (a) flipping through 70+ PDFs the day before the exam is a terrible idea, and (b) the bus ride home is too long to waste.

## A quick look

| Desktop — full study hub | Mobile — drill-down + flash cards |
|---|---|
| ![Desktop home](./screenshots/desktop_home.png) | ![Mobile home](./screenshots/mobile_home.png) |
| Sidebar nav · 12 weekly modules · cross-cutting themes · past-exam archive | Topic cards · prominent 🎴 Flash Cards entry · safe-area padding |

## What's inside

Two single-file web apps. No build step. No dependencies. Open the HTML, read the papers.

| File | What it's for | Best on |
|---|---|---|
| [`comps_review.html`](./comps_review.html) | The full desktop study hub — sidebar nav, side-by-side panels, past-exam questions, cross-cutting themes | Laptop / iPad with keyboard |
| [`comps_mobile.html`](./comps_mobile.html) | Distilled mobile drill-down — Home → Topic → Week → Paper, plus a shuffled **flash card deck** | Phone (subway, line at Starbucks, 3 AM panic) |

## Features

### Desktop (`comps_review.html`)
- **12 weekly modules** of the LEAD 601 syllabus, with curated takeaways for each of ~70 papers
- **Cross-cutting themes** (construct redundancy, leader-centric critique, levels of analysis, measurement validity, strategic & multilevel leadership) — the stuff exam questions actually probe
- **Past exam archive** with year-by-year questions you can practice against
- **Score-your-answer** practice mode for select questions

### Mobile (`comps_mobile.html`)
- **Drill-down nav**: Home → Leadership → Week N → Paper M, three taps deep, then a structured paper page
- **Per-paper detail**: ⭐ 3–4 sentence takeaway + 🎯 Research Question · 📚 Theory · 🔬 Method · 📊 Findings · 💡 Implications
- 🎴 **Flash Cards** — shuffled deck of all 84 readings
  - Tap to flip · swipe to advance · arrow keys on desktop
  - 🔀 Reshuffle anytime · ⏮ Restart · 📖 Jump straight to full paper detail
  - Progress bar so you know when the suffering will end
- iOS-style transitions and safe-area padding so the back button doesn't fight the home bar

## Why a mobile version?

Because comprehensive exams are not a one-week sprint, they're a six-month marathon. You read a paper today, forget it in two weeks, panic in three months. The mobile build is for **fragmented time** — those weird in-between minutes that would otherwise become Instagram. Open the app, tap "Flash Cards", get a random Yammarino paper, try to remember what WABA stands for, swipe to the next one.

Five minutes of flash cards on the bus, every day, adds up to a *lot* of repetition by November.

## The topics (12 weeks)

| Week | Topic |
|---|---|
| 1 | Overviews of Leadership |
| 2 | Leadership & Levels of Analysis |
| 3 | Leadership and Methods |
| 4 | Individual Differences & Behaviors |
| 5 | Contingency Models |
| 6 | Charismatic & Transformational |
| 7 | VDL, LMX & Individualized Leadership |
| 8 | Implicit Leadership & Followership Theories |
| 9 | Leader Development |
| 10 | Gender & Leadership |
| 11 | Measurement |
| 12 | What's Wrong with Leadership? |

Four other domains (Organizational Behavior, Research Methods, Strategy & OT) are stubbed in on the home screen and will get the same treatment as they're curated.

## Run it

No npm, no Vite, no Docker. Just:

```bash
# Local
open comps_review.html      # or comps_mobile.html

# Or visit the GitHub Pages link
# (see Settings → Pages once enabled)
```

Want it on your phone? Open the Pages URL in Safari → Share → **Add to Home Screen**. It runs full-screen like a native app.

## A note on the content

Summaries were assembled from the original PDFs read end-to-end (no skimming abstracts, no hallucinating from titles — that lesson was learned the hard way with Atwater et al., 2014). They're meant as **study scaffolds**, not substitutes for the readings themselves. If anything looks off, the PDF wins.

## License

The code is free for any doctoral student in distress to fork, copy, remix. The paper summaries are personal study notes — please don't paste them into your own dissertation.

---

*Made by a doctoral student, for the next doctoral student. Good luck out there.* 🫡
