# SOC Logbook

This folder is my dated record of SOC study and practice. It backs up the plan in the main README: Hack The Box Academy modules first, then Sherlocks, labs and a home lab, ending in a SOC Work-Integrated Learning (WIL) application on 14 December 2027.

Every entry is written the same day I study, so the commit history shows steady progress over time.

## Why I keep it

- **Proof of consistent work.** Employers (Take Note IT first) can see what I studied, when, and how long it took.
- **Learning.** Writing one thing I learned and one thing still unclear while it is fresh helps me remember it and shows me what to revisit before the exam.
- **Staying on schedule.** The Sunday review shows early if I am slipping against the module dates.
- **Portfolio material.** Module summaries and tickets become LinkedIn posts and interview examples.

## Folder layout

```
logbook/
  README.md          this file
  2026-W42.md        one file per ISO week (YYYY-Www.md)
  2026-W43.md
  ...
```

Each weekly file has one heading per study day. Related folders in the repo root:

| Folder | What goes in it |
| --- | --- |
| `/certificates` | Module badges |
| `/tickets` | Sherlock and lab write-ups (SOC-001, SOC-002, ...) |
| `/notes` | My own module notes, in my own words |
| `/detections` | Sigma and YARA rules, later on |

## When I write an entry

| When | What I write | Time |
| --- | --- | --- |
| Right after each study session | Date, module, sections done, time spent, one thing learned, one thing still unclear | 10-15 min |
| Same day a module is completed | Summary: module name, start and end dates, skills gained, badge link. Add the badge to `/certificates` and update the progress table in the main README | 20 min |
| Within 24 hours of finishing a module | LinkedIn post with the badge, 2-3 skills, and a link to my GitHub notes | 10 min |
| Within 24 hours of a Sherlock or lab | Full ticket in `/tickets` plus a one-line logbook entry pointing to it | 45-60 min |
| Every Sunday evening | Weekly review: what I completed, what slipped, next week's single goal | 20 min |

If I skip a day, I write it the next morning before starting new sections. I never let more than 2 days pile up. In CA test weeks I only write the one-line entry.

## Daily entry template

```
## <Weekday DD Mon> - <Module> sections <a-b>

Date: DD Mon YYYY | Module: <name> | Sections: <a-b> | Time: <n> min

Learned:
- ...

Still unclear:
- ...

Next session: sections <c-d>
```

## Rules for what I put in the logbook

This repo is public, so entries must be safe to share.

- Write in my own words. Do not paste from the Academy pages.
- **No answers or flags** for any question, challenge or Sherlock.
- **No target IP addresses, usernames or passwords** from the Academy "Connect to HTB" boxes.
- No screenshots of the question boxes. Screenshots of my own notes and commands are fine.
- Keep a Sherlock write-up in a private repo until HTB has retired that Sherlock.
- This is my own record. If Richfield requires its own WIL logbook format, I keep that separately once the placement starts.

## Commit message format

One commit per day, for example:

```
Logbook: 21 Oct, Linux Fundamentals 11-15
```

## Index

### Weekly files

| Week | File | Covers |
| --- | --- | --- |
| 2026-W42 | [2026-W42.md](2026-W42.md) | Linux Fundamentals sections 1-10 |
| 2026-W43 | [2026-W43.md](2026-W43.md) | Linux Fundamentals sections 11-17 |

### Module progress

| Module | Sections | Status | Badge |
| --- | --- | --- | --- |
| Linux Fundamentals | 30 | In progress (16 of 30 complete) | - |
| Windows Fundamentals | 15 | Not started | - |
| MITRE ATT&CK Framework | 9 | Not started | - |
| Event Log Analysis | 11 | Not started | - |

Update this table whenever a module is completed.
