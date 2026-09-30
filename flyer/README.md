# Elevated Media & Marketing — flyer images

Extracted from `claude/elevated-outreach-template.html` (the base64 data was stripped
out of that file's `<img>` tags for outreach drafts, since the Zapier Gmail draft
action can't reliably send ~340KB of inline base64 in one call).

12 files, 264KB total:

| File | What it is |
|---|---|
| `logo.png` | Header logo |
| `hero.jpg` | Hero/production still (top of flyer, under the intro blurb) |
| `work-01.jpg` – `work-10.jpg` | The 10-photo "Selected Work" grid, in the same left-to-right, top-to-bottom order they appear in the template |

## Setting this up on GitHub Pages

1. Create a new **public** repo (public is required for free GitHub Pages — private repos need a paid plan to serve Pages). Something like `elevated-media-assets`.
2. Drop these 12 files into it — either at the repo root or in a subfolder like `flyer/` (doesn't matter, just keep the path in mind for the URLs below).
3. In the repo's Settings → Pages, set the source to your default branch (e.g. `main`) and save. GitHub gives you a `https://<your-username>.github.io/<repo-name>/` base URL — takes a minute or two to go live the first time.
4. Each image's permanent URL is then:
   `https://<your-username>.github.io/<repo-name>/<path-if-any>/<filename>`
   e.g. `https://yourusername.github.io/elevated-media-assets/flyer/logo.png`

   (If you don't want to wait on Pages, a plain **public** repo also works without enabling Pages at all — raw file URLs like `https://raw.githubusercontent.com/<username>/<repo>/main/flyer/logo.png` load fine as email images too, and update instantly on every push. Pages is slightly more "proper" but raw.githubusercontent.com is simpler if you just want it working today.)

## Once you have the 12 URLs

Send them back to me (in whatever order — I'll match by filename) and I'll rebuild
`elevated-outreach-template.html` to reference those URLs instead of base64, and
save the updated version back to the project. After that, every future outreach
run can send the full photo flyer in a Gmail draft again, no workaround needed.
