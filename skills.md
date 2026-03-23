
# Data Story Reports

Create **zero-dependency, insight-first, narrative-driven HTML data reports** that run entirely in the browser.

---

## Core Principles

### 1. Insight First

* Data is not the goal — **understanding is**
* Every section must answer:
  → *“What does this mean?”*

### 2. Narrative Flow

Reports must read like a story:

```
What happened → Why it happened → What it means → What to do
```

### 3. Clarity Over Complexity

* If users need to think hard to understand it, the design has failed

### 4. Zero Dependencies

* Single HTML file
* Inline CSS / JS
* No build tools required

---

## Design Philosophy

Avoid the typical **“exported dashboard look”** (flat, noisy, unfocused)

### Focus on:

#### Hierarchy

* Title = **conclusion**
* Subtitle = **explanation**
* Charts = **evidence**

👉 Users should see the *insight first*, then the data

---

#### Color Semantics

* Colors must carry meaning:

  * Growth → positive / strong color
  * Decline → warning color
* Avoid rainbow palettes

---

#### Whitespace

* The more data → the more spacing needed
* Avoid visual clutter at all costs

---

#### Chart Discipline

* One chart = one message
* If text is clearer → **don’t use a chart**

---

## Standard Report Structure

### 1. Title Section

* Report title
* Time range
* One-sentence key takeaway

---

### 2. Key Insights

* 3–5 critical findings
* Each ≤ 2 lines
* Must be actionable or explanatory

---

### 3. Overview

* 3–6 KPI cards
* 1–2 core trend charts

---

### 4. Deep Dive

Each section answers **one question**

**Structure:**

* Question
* Chart (evidence)
* Insight (explanation)

---

### 5. Conclusion

* Summary of findings
* 2–4 action recommendations

---

## Layout Rules

Every section must include:

```css
min-height: 100vh;
```

### Requirements

* No overcrowding
* No visual noise

### Chart Constraints

```css
max-height: 50vh;
```

---

## Content Density Limits

| Section    | Maximum Content         |
| ---------- | ----------------------- |
| Title      | 1 heading + 1 subtitle  |
| Insights   | 3–5 items               |
| KPI        | up to 6 cards           |
| Deep Dive  | 1 chart + 1 explanation |
| Conclusion | up to 4 actions         |

👉 If exceeded, **split into multiple sections — never cram**

---

## Phase 0: Mode Detection

* **Mode A:** New Report
* **Mode B:** Data → Report (CSV / Excel / JSON)
* **Mode C:** Enhancement of Existing Report

---

## Phase 1: Data Discovery

Ask all at once:

### 1. Data Type

* Business / User / Financial / Other

### 2. Goal

* Reporting / Decision-making / Presentation / Analysis

### 3. Data Readiness

* Complete / Partial / Description only

### 4. Audience

* Executives / Team / Clients / Public

---

## Phase 2: Story Framing

Transform data into a structured narrative.

### Must answer:

* What happened?
* Why did it happen?
* What is the impact?
* What should be done?

👉 Generate **2–3 alternative story structures** for selection

---

## Phase 3: Report Generation

Generate HTML report with:

* Single-file HTML
* Inline CSS / JS
* Responsive layout
* Clear visual hierarchy
* Well-defined sections

---

## Chart Rules

| Chart Type | Use Case                    |
| ---------- | --------------------------- |
| Line Chart | Trends                      |
| Bar Chart  | Comparisons                 |
| Pie Chart  | Proportions (use sparingly) |
| Table      | Precise data                |

👉 When unsure, **prefer text over charts**

---

## Phase 4: Delivery

### Provide:

* File location
* Structure overview
* Key insights summary

### User can:

* Modify data
* Update content
* Adjust styling

---

## Anti-Patterns (Avoid)

* ❌ Chart overload
* ❌ Data without conclusions
* ❌ Decorative but meaningless animations
* ❌ Default color palettes
* ❌ Information overload

---

## Core Philosophy

* Data is not the goal → **Understanding is**
* Charts are not the goal → **Insight is**
* Reports are not the goal → **Decisions are**

---


