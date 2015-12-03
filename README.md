![](https://raw.githubusercontent.com/wr/figma-mac/master/extras/Example.png)

# Figma for Mac (unofficial)

This is an [Electron](https://github.com/atom/electron) wrapper for [Figma](https://figma.com). It lets you install Figma on your Mac and easily access it from the Dock instead of your web browser.

## Caveats

I'm not really a Node developer, so this is just a basic implementation. There are some known (and some unknown!) issues with this project:

- The Mac stoplights overlap the top navigation because I've chosen to use the `hidden-inset` `title-bar-style`. I've injected some CSS to fix it on launch, but it's buggy.
- Pinch to zoom does not work. I imagine this is solvable, but I don't know how.
- Files open in a new window :[
- This is a third-party project not associated with Figma, Inc., so use it at your own risk.

## How to Install

1.