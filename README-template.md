# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

VSCode
...Help from Chatgbt :D

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

First thing was the different media sizes and how much different they look. It's kind of tricky working with this kind of stuff.

I learned the hard way, that the lower css rule overrules the upper one, even if it's a special rule. That's why the :media /*Desktop*/ is now placed at the bottom of the page.

Also I really struggled with the Button, because I didn't get, why it overflowed all the time. Seems like all:unset also removes the border settings. So border-box was (after some intensified feelings) the fix I needed.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
@media (min-width: 768px) {
    .bigbox {
      flex-direction: row;
        max-width: 700px;
    }
  
    .imagebox {
      width: 50%;
      height: auto;
      background-image: url('https://raw.githubusercontent.com/workname-wizard/fm_product_preview_card_component/main/product-preview-card-component-main/images/image-product-desktop.jpg');
    }
  
    .textbox {
      width: 50%;
      padding: 2rem;
    }
  }
  really proud of understanding how this thing works. Even if I needed help setting up.


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

There is a lot of work for me to do in CSS. I mean I get the colors and text editing stuff, but as soon as it goes deeper, I see that theres not really much knowledge. Mentioning that I started coding like 1 Month ago and managed to do more for 4 days at this point.

I'll do the FreeCodeCamp Fullstack Certificate. At least as long as I can manage it.

### Useful resources

- [Example resource 1]ChatGbt- I mean, it's not perfect at all, especially if you let it Code for you. But if you use it as a Coach, that won't code anything for you, only to lead you on the right path, it's actually a great help.


## Author

- Website - [Felix Aschengschwandtner](https://github.com/workname-wizard)
- Frontend Mentor - [@workname-wizard](https://www.frontendmentor.io/profile/workname-wizard)

