# China University SOP Reviewer & Narrative Strategy Skill for Claude

An AI-assisted Standard Operating Procedure (SOP) and Claude Custom Skill designed for teachers, counselors, and academic advisors. This tool conducts diagnostic narrative reviews and minimal grammar editing for student admissions essays targeting top Chinese universities (e.g., Tsinghua, Peking, Fudan).

## Key Features

- **80/20 Flow-First Framework:** Prioritizes overall narrative arc, prompt coverage, and structural flow over line-by-line critiques.
- **Direct Red-Text Grammar Edits:** Corrects syntax and punctuation errors directly within the text using red markup without altering student phrasing.
- **Authentic Voice Preservation:** Strictly forbids AI ghostwriting, synthetic embellishment, or inventing false student experiences.
- **Comment Budgeting:** Limits feedback to 2–3 high-impact actionable margin notes to prevent student overwhelm.

## Repository Contents

- `SKILL.md`: The system prompt / skill definition file ready to import into Claude.
- `SOP_China_Admissions.md`: The complete reference standard operating procedure for human reviewers.

## How to Install & Use in Claude

### Option A: Claude Projects (Recommended)
1. Open **Claude.ai** and navigate to your **Project**.
2. Click **Project Knowledge** and upload `SOP_China_Admissions.md`.
3. Open **Set Project Instructions** and copy-paste the contents of `SKILL.md`.

### Option B: Custom Instructions / System Prompt
1. Copy the contents of `SKILL.md`.
2. Paste into your custom instruction box or system prompt field in your AI workflow tool.

### Option C: Standalone Chat Usage
Paste the content of `SKILL.md` into your conversation with Claude before submitting the application prompt and student draft.

## Example Trigger Prompt

```text
Read the attached SOP draft against the prompt [Insert Prompt] and word limit [Insert Limit] for [University Name]. Apply the 80/20 Flow-First review: provide the top red flow note, direct red grammar edits in text, and 2-3 priority margin comments. Preserve my authentic voice and do not rewrite my essay.
