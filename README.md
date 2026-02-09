## 📄 `README.md`

# Writing Skills System

This repository defines a modular writing system based on **explicit writing contracts** (“skills”).
Each skill corresponds to a distinct type of text, with its own rules of tone, structure, rigor, and citation.

The goal is to avoid generic writing behavior and ensure that each document is produced under the correct stylistic and methodological constraints.

---

## Core Principle

> **One file, one dominant writing skill.**

Each document must be written using the skill that best matches its primary purpose.
Skills are not interchangeable.

---

## Directory Structure

```text
skills/
├── literary-fiction/
│   └── SKILL.md
├── literary-essay/
│   └── SKILL.md
├── academic-writing/
│   └── SKILL.md
├── scientific-article/
│   └── SKILL.md
└── technical-writing/
    └── SKILL.md
```

Each folder contains a single `SKILL.md` file that defines a complete writing contract.

---

## Skill Overview and Usage

### 1. Literary Fiction (`literary-fiction`)

**Use when writing:**

* Novels
* Short stories
* Novellas
* Fictional chronicles

**Defining traits:**

* Narrative-driven prose
* Strong authorial voice
* Stylistic freedom
* No mandatory references

**Primary goal:**
Voice, rhythm, and narrative presence.

---

### 2. Literary Essay / Authorial Non-Fiction (`literary-essay`)

**Use when writing:**

* Essays
* Cultural criticism
* Philosophical reflections
* Hybrid analytical-literary texts

**Defining traits:**

* Free argumentation
* Authorial perspective
* Optional references
* Reflective and exploratory tone

**Primary goal:**
Thinking through writing, not formal demonstration.

---

### 3. Academic Writing (`academic-writing`)

**Use when writing:**

* Academic books
* Theoretical chapters
* Dissertations
* Theses

**Defining traits:**

* Formal academic language
* Logical and hierarchical structure
* Mandatory references
* Detailed explanation

**Primary goal:**
Scholarly rigor with explanatory clarity.

---

### 4. Scientific Article (`scientific-article`)

**Use when writing:**

* Journal articles
* Conference papers
* Preprints

**Defining traits:**

* IMRaD structure
* High citation density
* Extreme conciseness
* Methodological discipline

**Primary goal:**
Precise scientific communication.

---

### 5. Technical / Didactic Writing (`technical-writing`)

**Use when writing:**

* Manuals
* Didactic books
* Documentation
* Guides and tutorials

**Defining traits:**

* Clarity over style
* Step-by-step explanations
* Examples and instructions
* Optional references

**Primary goal:**
Usability and comprehension.

---

## Typst and LaTeX Compatibility

All skills are designed to be compatible with **Typst** and **LaTeX**.

* Citation behavior is explicitly defined per skill
* Reference integrity is mandatory where applicable
* Structural discipline aligns with academic and technical typesetting workflows

Skills do not prescribe syntax, only writing behavior.

---

## Humanization Policy

All skills include explicit **humanization constraints** to avoid mechanical or template-like prose.

Humanization is:

* Extensive in literary writing
* Moderate and controlled in academic writing
* Minimal and functional in scientific and technical writing

Human variation must never compromise clarity, rigor, or reproducibility.

---

## How to Choose the Correct Skill

Ask one question:

> **What is the primary purpose of this document?**

* Tell a story → `literary-fiction`
* Reflect or argue freely → `literary-essay`
* Explain theory rigorously → `academic-writing`
* Report scientific results → `scientific-article`
* Teach or instruct → `technical-writing`

If in doubt, choose the more restrictive skill.

---

## Recommended Workflow

1. Select the appropriate skill for the document
2. Apply the rules defined in `SKILL.md`
3. Write without mixing writing contracts
4. Revise using the same skill
5. Only switch skills when starting a new document

---

## Final Note

This system is designed to prioritize **clarity of intent, stylistic coherence, and long-term reuse**.
It favors explicit constraints over generic flexibility.

> Good writing starts with choosing the right rules.
