# yossi-eynav.github.io

The GitHub Pages user site for `yossi-eynav`, served at <https://yossi-eynav.github.io/>.

Its main job is to prove ownership of the `yossi-eynav.github.io` domain to Google, so that
Glimpse's privacy policy and terms (published from the
[glimpse](https://github.com/yossi-eynav/glimpse) repository at
<https://yossi-eynav.github.io/glimpse/>) can be used on Google's OAuth consent screen.

## Google Search Console verification

1. In [Search Console](https://search.google.com/search-console), add a **URL prefix** property
   for `https://yossi-eynav.github.io/`.
2. Choose **HTML file**, and download the `google<code>.html` file.
3. Commit that file, unchanged, to the root of this repository and push.
4. Wait about a minute for Pages to publish it, then click **Verify**.

**Keep the file here.** Google checks it again later, and removing it can make the domain
unverified.

## Notes

- Pages settings: **Deploy from a branch**, `main`, `/ (root)`.
- `PRIVACY.md` and `TERMS.md` are copies of the files in the glimpse repository. GitHub Pages'
  Jekyll build renders them at `/PRIVACY.html` and `/TERMS.html`. Edit them there and copy them
  again; don't edit them here.
- Don't add a `glimpse/` folder here. That path belongs to the glimpse repository's own Pages
  site.
