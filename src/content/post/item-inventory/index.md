---
title: "Item Inventory"
description: "A list of all of my physical possessions"
publishDate: "2024-02-22"
tags: ["minimalism"]
draft: true
---

## Books

- [生の短さについて](https://www.iwanami.co.jp/book/b246664.html) - セネカ 著、大西英文 訳
- [ノルウェイの森（上）](https://bookclub.kodansha.co.jp/product?item=0000203588) - 村上春樹 著
- [ノルウェイの森（下）](https://bookclub.kodansha.co.jp/product?item=0000203589) - 村上春樹 著
- [汝、星のごとく](https://bookclub.kodansha.co.jp/product?item=0000366625) - 凪良ゆう 著
- [星を編む](https://bookclub.kodansha.co.jp/product?item=0000379789) - 凪良ゆう 著
- [ゴールデンスランバー](https://www.shinchosha.co.jp/book/459603/) - 伊坂幸太郎 著
- [Cybersecurity Myths and Misconceptions](https://www.oreilly.com/library/view/cybersecurity-myths-and/9780137929214/) - Eugene H. Spafford, Leigh Metcalf, Josiah Dykstra
- [A Vulnerable System](https://www.cornellpress.cornell.edu/book/9781501758942/a-vulnerable-system/) - Andrew J. Stewart

## Gadgets

- M1 Pro MacBook Pro (32GB RAM, 1TB SSD)
- ZSA Voyager
- iPhone SE (2nd generation)

## Documents and Stationery

- Passport
- Banking file
- Physical cards
- SARASA ballpoint pen
- Maruman original paper
- PwC paper file

## Clothing

- 8x Uniqlo U t-shirt
- 3x Uniqlo pants
- 8x Airism shirts
- 8x Airism underwear
- 6x MUJI hand towels

## Kitchen

## This is a H2 Heading

### This is a H3 Heading

#### This is a H4 Heading

##### This is a H5 Heading

###### This is a H6 Heading

## Horizontal Rules

---

---

---

## Emphasis

**This is bold text**

_This is italic text_

~~Strikethrough~~

## Quotes

"Double quotes" and 'single quotes'

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...

## References

An example containing a clickable reference[^1] with a link to the source.

Second example containing a reference[^2] with a link to the source.

[^1]: Reference first footnote with a return to content link.
[^2]: Second reference with a link.

If you check out this example in `src/content/post/markdown-elements/index.md`, you'll notice that the references and the heading "Footnotes" are added to the bottom of the page via the [remark-rehype](https://github.com/remarkjs/remark-rehype#options) plugin.

## Lists

Unordered

- Create a list by starting a line with `+`, `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    - Ac tristique libero volutpat at
    - Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
- Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

4. You can use sequential numbers...
5. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

Block code "fences"

```
Sample text here...
```

Syntax highlighting

```js
var foo = function (bar) {
	return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

## Images

Image in the same folder: `src/content/post/markdown-elements/logo.png`

![Astro theme cactus logo](./logo.png)

Image in the aliased assets folder: `src/assets/about-astro.png`

![A cartoon cactus looking at the Astro.build logo](@/assets/about-astro.png)

## Links

[Content from markdown-it](https://markdown-it.github.io/)
