# brew.sh
[![Azure Pipelines](https://img.shields.io/vso/build/Homebrew/56a87eb4-3180-495a-9117-5ed6c79da737/9.svg)](https://dev.azure.com/Homebrew/Homebrew/_build/latest?definitionId=9)

The webpage uses [jekyll](https://github.com/jekyll/jekyll). The template for
the index is at `_layouts/index.html`.

## Translations

### GitHub Pull Request

If you want to add a new translation, follow these steps:

1. Copy `index.html` to `index_{langcode}.html`
2. Copy `_data/locales/en.yml` to `_data/locales/{langcode}.yml`
3. Change the values of the English strings to the translated, new language strings.

You can see the translated webpage by running `jekyll serve` and opening
<http://localhost:4000/>

### Transifex

[Help Translate "Homebrew homepage"](https://www.transifex.com/homebrew/homebrew-homepage/dashboard/) on Transifex.
