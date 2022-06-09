# Introduction 
This is the code that is used to build the Baarlo website. Changes to the `main` branch will be automatically built using pipelines and will be hosted using Github Pages (static content at `gh-pages` branch).

# Getting started
This is how it works:
- Changing the content: You can change the content of the pages by editing the `content/*.md` files.
- Adding static content: Static content like images can be added to the `static/` folder. Images can be added to the `static/images/` folder.
- Adding menu items: More menu items can be added by adding a new `[[languages.en.menu.main]]` section in `config.toml`. Be aware that you also have to create the accompanying `.md` file in the `content/` folder.

The theme that was used is the "Hugo Coder" theme. It is referenced as a Git submodule in `themes/hugo-code`. Some nice examples can be found at:
- [Visual examples](https://hugo-coder.netlify.app/posts/)
- [Code examples](https://github.com/luizdepra/hugo-coder/tree/2b8d4c11435fd598ca133ffe8288639a08079224/exampleSite/content/posts)
