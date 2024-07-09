# Quarto Website Template

This repository serves as a template for creating a website rendered from markdown files using Quarto. It provides a starting point for building a website with Quarto. 

To individualize content, change the following:

1. state project information in this [`README.md`](/README.md)
2. individualize content of the main (starting) page in [`index.qmd`](/index.qmd) 
3. (optionally) add futher content in additional pages ([`subpage.qmd`](/subpage.qmd) is initialized as starting point)
4. customize content in the [`_quarto.yml`](/_quarto.yml) file
   - change `site_url`, `repo_url` and under *page footer* `href` to point to the new repo
   - (optionally) change all the other links pointing to personal social media sites etc.
   - (optionally) add additional pages such as `subpage`
5. (optionally) change the style of the website (fonts, colors,...) in the [`custom_theme.scss`](/custom_theme.scss) file. 


The website is rendered with Quarto either locally (has to be installed) or automatically via Github Actions each time new content is added/changed (merged pull requests). The Html-site is created in the `_site` folder (do not change anything in there manually). In order to make Github actions work you have to change the repository settings under `Settings` / `Pages` / `Source` to `Github Actions`.

To add citations you can add a bibliography file (e.g. `references.bib`) and reference it in the `_quarto.yml`. Further information about this [here](https://quarto.org/docs/visual-editor/technical.html#citations). Using [Zotero](https://www.zotero.org/), along with [Better BibTex](https://retorque.re/zotero-better-bibtex/installation/) and then e.g. the [Zotero Citation picker extension](https://github.com/mblode/vscode-zotero) in VSCode is a good way.


## Info

- Helpful tutorials and examples on Quarto in general are listed in the [awesome-quarto repository](https://github.com/mcanouil/awesome-quarto).
- Good resources about creating websites with Quarto by [Samantha Csik](https://ucsb-meds.github.io/creating-quarto-websites/).
- Style adaptations in this repo adapted from [Ella Kaye's website](https://github.com/EllaKaye/ellakaye.co.uk).
- Another helpful template repository was the [NOAA-quarto-simple template](https://github.com/nmfs-opensci/NOAA-quarto-simple).
- Github Action Workflow adpated from [tarleb.com](https://tarleb.com/posts/quarto-with-gh-pages/#actions-only-pages-beta).
- Good resource on color choice and fonts from [emilhvitfeldt.com](https://www.emilhvitfeldt.com/post/slidecraft-colors-fonts/)
- Tool to check color contrasts: https://colourcontrast.cc/