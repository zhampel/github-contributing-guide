# github-contributing-guide

Slides providing overview of contributing with teams to GitHub repos.

Online slides can be found [here](https://zhampel.github.io/github-contributing-guide/#/).

## Usage

The slides for this talk can be generated via:

```bash
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt

jupyter nbconvert github-contributing-guide-slides.ipynb --to slides --post serve --template output_toggle.tpl --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_theme=serif
```
