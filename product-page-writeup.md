# Product Landing Page Write Up

## [Codepen Link](https://codepen.io/wilsonj806/full/ZRxYzK/)

## [Live Site](https://wilsonj806.github.io/blackbox-landing/)

## Date Created: 06/29/2018

## Requirements:

Requirements done by FCC and [Link here](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-product-landing-page/)

## Personal Requirements:

- Use OSHA Yellow in the color palette
- Add at least one table
- Try not to use black as a background color
- One section needs to be done in Flexbox


## Things learned

- File extensions are case sensitive to a large amount of things
- There's a Bootstrap CSS and Bootstrap JS
- Collapse.JS from Bootstrap requires `bg-dark` and `navbar-dark` (or light) to be called
-

## Workflow consistency in comparison with the last projects

- Continued using Figma to mockup layouts and wireframes
    - [General link here](https://www.figma.com/file/bpdAsf1BWEJCEeWwtMr6PPxh/Product-Page-Mock)
- Continued using semantic class names
    - Formatted so class names largely read like so: ` identifier --> application ` 
        - e.g `.ctr-ftr` = `container-feature`
- Continued using Semantic Versioning
- Continued focusing more on rapid iteration over getting everything perfect in one go

## Process changes from the last projects

- Less use of Github branching to approve stuff and push things upwards
    - Could be because I knew what I wanted the page to look like, whereas in the Portfolio project it was more hazy
        - Either way, there's a balance between not branching and branching too much
- Less use of the `test.html` file although that could be because many features could be tested fast or were straight-forwards to implement
- Less time spent figuring out the color palette since there were two primary colors
- Tried not styling each and every element and instead styling numerous elements at once and just reused them, kept the style simple, or just overwrote styles in separate classes
- Added more specific requirements for more targeted learning (e.g make a table, or using OSHA yellow) 
- Started using Emmet more

## Process changes to make for future projects

- Have a folder of various sized "prebaked" images for placeholders instead of scrounging for them
    - Pictures should be relatively diverse in color
- Keep project notes separate from the main `index.html` file
- Remove class declarations in the `html` file if you don't intend on using them
    - e.g `<div class=""></div>`
- Maybe focus more on having something usable ready and releasing it for v1.0.0 versus agonizing over the implementation of certain things
    - The goal is to have something that's functional and can be built on based on lessons learned during that project
        - Basically want something that's like the [Survey Form](https://wilsonj806.github.io/survey-form/) project or even this project: completed and clean implementation of features, but also leaving room to patch things that might take too long to debug
        - TL; DR The goal for the FCC projects is to learn, not to ship out client-ready things (save for the portfolio). Focus on learning as much as possible and making the code clean enough for future maintenance
