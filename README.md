# 🧠 QA-PRO-Preparation

Interactive interview-preparation dashboard for **Junior+ QA Engineer** roles — a single-page HTML app with flashcards, quizzes, cheat sheets, project stories, a dedicated company-specific battle tab, market notes, and a 4-week revision plan.

> Personal QA interview cockpit: Manual QA, API, Java, Selenium, SQL, Git, CI/CD, Onyx project preparation, and ready-to-use interview scripts in RU/EN/DE.

---

## 🎯 What's Covered

| Section | Access | Content |
|---|---|---|
| **QA Interview Q&A** | open | 130+ flashcards across Manual QA, API, Selenium, Java, SQL, Git, Frontend, Python, Mobile, BDD, CI/CD, Agile |
| **Quiz Mode** | open | 40+ multiple-choice questions with explanations and topic filters |
| **Cheat Sheets** | open | Compact reference blocks: status codes, SQL, Git, Java, Selenium, API, Docker, CI/CD, BDD, mobile |
| **Skills Matrix** | open | MUST / SHOULD / PLUS / WOW priority map for Junior QA |
| **Top Questions** | open | Frequently asked interview questions tagged HOT / CLASSIC / TREND |
| **Companies** | open | DE / EU / international employers, expected stack, salary ranges |
| **4-Week Plan** | open | Step-by-step revision: Manual QA → API → Java/Selenium → SQL/Interview |
| **Resources** | open | Courses, YouTube channels, interactive practice sites, docs, job platforms |
| **🎯 TKI Battle Tab** | code | Company-specific prep: self-intro, bug stories, REST Assured structure, PostgreSQL/Oracle, scenario questions, document-risk answers, TKI Q&A bank + TKI quiz |
| **ONYX TaskTracker** | code | Project architecture, QA contribution, automation stack, STAR story |
| **Cheat Code Formula** | code | Universal structure for answering interview questions in 30–60 seconds |
| **Interview Scripts** | code | Ready answers in RU / EN / DE for common HR/technical questions |
| **Checklist** | code | Preparation checklist with saved progress |
| **Market Overview** | code | Salary ranges, job boards, personal advantages, study strategy |

---

## 🔐 Access Levels

The dashboard separates open study material from personal data. The repository is public, so a passcode keeps personal sections from casual view.

| Zone | Code |
|---|---|
| Home + general study tabs (Q&A, Quiz, Cheat Sheets, Skills, Top Questions, Companies, Plan, Resources) | **open — no code** |
| Personal sections (ONYX, Cheat Code, Scripts, Checklist, Market) | **1642** |
| TKI Battle tab | **2026** (separate code) |

> Note: codes live in the client-side HTML, so this protects against casual viewing and indexing — not against someone reading the page source. For real privacy, host privately or behind server-side auth.

---

## 🧰 Tech Stack

- **HTML5** — single-page structure
- **CSS3** — responsive layout, dark/light theme, card-based UI
- **Vanilla JavaScript** — navigation, quiz logic, progress tracking, flashcards, section gating
- **sessionStorage / localStorage** — unlock state per session, study progress and theme
- **No backend** — runs locally or directly from GitHub Pages

---

## 🏗️ Project Structure

```
.
├── index.html       # Full QA preparation dashboard: UI + styles + JavaScript
└── README.md        # Project documentation
```

---

## 🔑 Key Features

### Interactive dashboard
A browser-based study tool with navigation tabs, progress tracking, flashcards, quiz mode with scoring, and topic-based sections — not a static note file.

### QA interview focus (Junior+)
Content is organized around real interview preparation:

- Manual QA fundamentals, 7 ISTQB testing principles, test design (EP, BVA, decision tables)
- Bug reports, severity vs priority, root-cause analysis
- API testing, REST principles, HTTP status codes, JWT, idempotency
- Java basics for QA automation (OOP, collections, exceptions, String/StringBuilder)
- Selenium WebDriver, waits, locators, POM, flaky-test handling
- SQL and database checks (JOINs, GROUP BY/HAVING, indexes, ACID, normalization)
- Git, CI/CD, Docker, BDD, mobile testing basics
- Agile/Scrum, Definition of Done, shift-left testing

### TKI Battle tab
A dedicated, code-protected tab tailored to a specific Software Test Engineer vacancy (telecom/fiber-network software):

- 45-second self-introduction and 90-second project answer
- Bug stories with Symptom → Cause → Found → Outcome structure
- REST Assured test structure based on the real Onyx framework
- PostgreSQL / Oracle dialect comparison and SQL deep-dive
- Scenario-based questions (login testing, incomplete requirements, prod bug, flaky UI)
- Document-risk prep (CV vs Zeugnis wording, German level, course-vs-project honesty)
- TKI-specific Q&A bank and quiz

### ONYX project preparation
A section for explaining the **Onyx TaskTracker QA project** in interview format:

- backend / frontend / QA architecture overview
- API + UI automation contribution (Java 17, REST Assured, TestNG, Gradle)
- JWT / cookies / API-flow understanding
- STAR-style project story
- improvement points and realistic next steps

### Cheat Code answer formula
A simple framework for structuring interview answers:

1. Give a short definition
2. Explain why it's needed
3. Explain how it works
4. Mention the trade-off / common mistake
5. Connect it to a real Onyx example

### Multi-language interview scripts
Ready-to-use answers in:

- **RU** — for preparation and self-explanation
- **EN** — for international companies
- **DE** — for German HR/interview situations

---

## 🚀 How to Run

### Option 1: Open locally
Download the repository and open `index.html` in any modern browser.

```bash
git clone https://github.com/xscofild/QA-PRO-Preparation.git
cd QA-PRO-Preparation
```

Then open `index.html` in your browser.

### Option 2: Run with VS Code Live Server
1. Open the project in VS Code
2. Install the **Live Server** extension
3. Right-click `index.html`
4. Select **Open with Live Server**

### Option 3: Publish with GitHub Pages
1. Open repository **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Save and wait ~1–2 minutes for deployment

---

## 📌 Best Use Case

Use this project as a daily interview-preparation tool:

| Situation | Recommended Section |
|---|---|
| Fast daily repetition | Q&A flashcards |
| Weak theory topic | Cheat sheets |
| Before a technical interview | Top questions + quiz |
| Before an HR interview | Scripts RU/EN/DE |
| Preparing for a specific TKI interview | TKI Battle tab |
| Explaining portfolio | ONYX TaskTracker section |
| Planning a study week | 4-week plan |

---

## 📝 Notes

- This is a **personal learning and interview-preparation project**, not a production SaaS application.
- It is intentionally kept as a single `index.html` file to make it easy to open, move, publish, and maintain.
- Content focuses on **Junior+ QA Engineer** roles in Germany/EU with emphasis on API testing, UI automation, Java, Selenium, REST Assured, SQL, and practical interview readiness.
- Access codes are basic client-side protection only.
- Future improvements: split into separate files, JSON-based question storage, keyword search, exportable progress reports.

---

## 🎓 Author

**Serdar Kerimov** — [github.com/xscofild](https://github.com/xscofild) · [LinkedIn](https://www.linkedin.com/in/serdarkerimov/)
QA Engineer | Java · Selenium · REST Assured · SQL
