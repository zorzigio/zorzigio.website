# ['zorzi.dev'](https://zorzi.dev/)

Hello there! You have reached the behind-the-scene of ['zorzi.dev'](https://zorzi.dev/)

## About the site

['zorzi.dev'](https://zorzi.dev/) is built using [Hugo](https://gohugo.io/), a very fast static site generator built in golang that translates markdown files into websites.
The base theme I am using is [PaperMod](https://github.com/adityatelange/hugo-PaperMod) but I heavily modified it to fit my needs.

## Development

Create a new post

```bash
hugo new folder/post.md
```

Serve

```bash
hugo serve
```

and then reach the website at [localhost:1313](http://localhost:1313)

## Check links

This uses [hydra](https://github.com/victoriadrake/hydra-link-checker) to check for broken links.

```bash
python hydra.py http://localhost:1313
```
