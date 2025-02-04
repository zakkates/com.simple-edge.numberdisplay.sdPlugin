TODO: UPDATE README
`NumberDisplay` is a sample plugin demonstrating the [Stream Deck SDK](https://developer.elgato.com/documentation/stream-deck/).

# Description

`NumberDisplay` is a plugin that displays a number chosen by the user. This plugin demonstrates how to create a custom Property Inspector and how to pass values from Property Inspector's input controls to the plugin.

# Features

- code written in Javascript
- cross-platform (macOS, Windows)
- Property Inspector with multiple UI elements
- localized

![](screenshot.png)

# Installation

In the Release folder, you can find the file `com.simple-edge.numberdisplay.sdPlugin`. If you double-click this file on your machine, Stream Deck will install the plugin.

# Build

[Stream Deck Developers: Packaging](https://developer.elgato.com/documentation/stream-deck/sdk/packaging/)

- Have the Distribution Tool in your StreamDeck Directory
- Run the Distribution Tool in Terminal
  /Users/zakkates/Library/Mobile\ Documents/com\~apple\~CloudDocs/Development/StreamDeck/DistributionTool -b -i Sources/com.simple-edge.numberdisplay.sdPlugin -o .

# Source code

The Sources folder contains the source code of the plugin.
