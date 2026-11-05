# Yash Todi

**Co-founder & COO, The Lemon Bowl · Ex-McKinsey · Building AI tools for real business operations**

I co-founded The Lemon Bowl, a premium platter and catering business in Delhi NCR, and ran it as COO. I built its operating infrastructure, sales engine and a 35+ person team, took it from a home kitchen to 5,000+ deliveries a year, and made it profitable in under 5 months.

Before that, I was Chief of Staff at an early-stage consumer startup in New York, and spent 6+ years at McKinsey working with C-suite leaders on strategy, operating cadences and governance, and deploying AI platforms inside client environments.

The work I enjoy most is finding where a business is slow, manual or error-prone, and building the process or tool that fixes it. At McKinsey that meant planning cycles, dashboards and executive reporting that leadership teams ran on. At The Lemon Bowl it now means AI agents. This page is where I share them: what each one solves, how it works, and the decisions behind it.

**Start here:** the [Sales Copilot](https://github.com/ytodi96/lemonbowl-sales-copilot) (an AI agent drafting quotes and replies for a real business), the [Eval & Rubric Studio](https://github.com/ytodi96/eval-rubric-studio) (how I measure AI quality), or the [live website demo](https://ytodi96.github.io/lemonbowl-website/).

## AI across one real small business: The Lemon Bowl

One catering business, end to end: getting found, converting enquiries, repeat orders and the numbers behind it all.

| Solution | Problem | Status | Link |
|---|---|---|---|
| Website | Customers couldn't plan an event online: no way to see how dishes scale with guest count, customise them, or request a catering quote without a long WhatsApp thread. | 🟡 Prototype (demo live) | [Live demo](https://ytodi96.github.io/lemonbowl-website/) · [Code](https://github.com/ytodi96/lemonbowl-website) |
| Sales Copilot | The sales rep spends hours building menus, quoting orders and handling customer issues on WhatsApp. This AI copilot drafts all three for the rep to approve. | 🚧 In build | [Code](https://github.com/ytodi96/lemonbowl-sales-copilot) |
| Customer Retention & Upsell Agent | Most revenue comes from repeat customers, but nobody tracks who ordered when or when to reach out, so festive repeats and catering upgrades get missed. | 📋 Planned | Coming soon |
| Finance Copilot | The books are spread across accounting exports, bank statements and spreadsheets, so questions like "why was October's margin down?" take days to answer. | 📋 Planned | Coming soon |

## Reusable AI tools

| Solution | Problem | Status | Link |
|---|---|---|---|
| Eval & Rubric Studio | Teams ship AI features without knowing whether outputs are good, or whether a prompt change made things better or worse. | 🚧 In build | [Code](https://github.com/ytodi96/eval-rubric-studio) |
| Trip Planner Research Agent | Planning a trip means hours across Reddit, blogs and YouTube. This agent researches them, ranks places by how many sources agree, and builds a cited day-by-day plan. | 📋 Planned | Coming soon |

## How I build

1. **I own the thinking.** I define the problem, the user and what "good" looks like before I open an AI tool. AI speeds up the build. The judgement on what to build, and whether it works, stays with me.
2. **Context in, quality out.** I brief a model the way I'd brief a new team member: the goal, the constraints, real (anonymised) examples and the exact output I want back.
3. **Small steps, checked as I go.** I break work into pieces I can review one at a time, rather than one big prompt and a hope.
4. **The LLM decides and writes, code does the maths.** Models handle judgement and language. Prices, totals and dates come from plain code, so they're consistent and testable.
5. **A human approves every customer message.** Agents draft. A person reviews and sends.
6. **Every agent ships with evals.** I test against real scenarios and edge cases before I trust the output, and rerun the tests whenever something changes.
7. **Decisions get written down.** Each project keeps a build log of what I tried, what I dropped and why.
8. **Privacy first.** Real customer data stays private. Public repos only ever hold anonymised sample data.
