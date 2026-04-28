# CLAUDE.md — Project Instructions

## What This Project Is
<!-- 1-2 sentences: what does this project do and why does it exist? -->
[DESCRIBE YOUR PROJECT HERE]

## Tech Stack
<!-- What frameworks, libraries, APIs are in use? -->
- [e.g. React + Vite, Tailwind CSS]
- [e.g. Claude API via Anthropic SDK]
- [e.g. Deployed on Vercel / GitHub Pages]

## How to Run Locally
```bash
# [fill in your actual commands]
npm install
npm run dev
```

---

## Coding Conventions
- [e.g. Use TypeScript strictly — no `any`]
- [e.g. Components go in /src/components, one file per component]
- [e.g. CSS via Tailwind utility classes only, no custom CSS files]

---

## End-of-Session Checklist (REQUIRED)

After every coding session, before finishing, you MUST:

1. **Update README.md** to reflect current project state:
   - Keep the "What it does" section accurate to what's actually built
   - Update the "Features" list to match what's currently working
   - Update the "Status" badge/line (e.g. "MVP complete", "In progress", "Stable")
   - Add anything notable to the "Changelog" section at the bottom

2. **Commit all changes** with a descriptive conventional commit message:
   ```
   feat: add X feature
   fix: resolve Y bug
   refactor: restructure Z component
   docs: update README with current feature state
   ```
   Group logical changes. Don't commit broken builds.

3. **Push to main** (or open a PR if on a feature branch):
   ```bash
   git add -A
   git commit -m "[your descriptive message]"
   git push origin main
   ```

4. **If there's a live demo URL** — verify it still deploys correctly after your push.

---

## Portfolio Sync (Optional — if you have a portfolio repo)

After pushing, also update the central portfolio repo if:
- The project name or description changed
- A significant new feature was added
- The project status changed (e.g. went from "in progress" to "complete")

To do this:
```bash
# From your portfolio repo directory:
# Edit projects.json to update this project's entry, then:
git add projects.json
git commit -m "portfolio: update [PROJECT NAME] status/description"
git push origin main
```

---

## README Template

Keep your README.md in this shape:

```markdown
# [Project Name]

> [One-line description]

**Status:** [In Progress / MVP Complete / Stable / Archived]  
**Live demo:** [URL or "N/A"]  
**Built with:** [tech stack, comma-separated]

## What it does
[2-3 sentences describing what the app does for a non-technical reader]

## Features
- [Feature 1]
- [Feature 2]
- [Feature 3]

## Screenshots
<!-- Add at least one screenshot or GIF when the project is demo-ready -->

## How to run locally
\`\`\`bash
npm install
npm run dev
\`\`\`

## Changelog
- **[Month Year]** — [What changed]
- **[Month Year]** — [Initial build]
```
