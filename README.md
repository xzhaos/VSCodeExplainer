# Code Explainer


[![version](https://img.shields.io/visual-studio-marketplace/v/xzhaos.code-explainer)](https://marketplace.visualstudio.com/items?itemName=xzhaos.gemini-code-explainer)
[![installs](https://img.shields.io/visual-studio-marketplace/i/xzhaos.gemini-code-explainer)](https://marketplace.visualstudio.com/items?itemName=xzhaos.gemini-code-explainer)
[![rating](https://img.shields.io/visual-studio-marketplace/r/xzhaos.gemini-code-explainer)](https://marketplace.visualstudio.com/items?itemName=xzhaos.gemini-code-explainer)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![github](https://img.shields.io/badge/github-green)](https://github.com/xzhaos/codeExplainer)



### This is a VS Code extension that explains every bit of code inside your editor. It uses the Gemini API to generate explanations for code. 

Adapted from (https://github.com/Sadeedpv/codeExplainer/blob/main/assets/code-explainer-logo.png?raw=true). Many thanks to @Sadeedpv. 

Code repository (https://github.com/xzhaos/VSCodeExplainer)

## Installation

To install the extension, open VS Code and go to the Extensions tab. Search for **Code Explainer** and click Install. Alternatively, You can install it from [here](https://marketplace.visualstudio.com/items?itemName=xzhaos.gemini-code-explainer)

## WHY YOU SHOULD USE IT?

- You have trouble understanding an open-source project.
- Or Maybe you just copied the code from Stack Overflow or some other site, and you don't understand what you've just written.
- You can also tell AI to generate the code you want by selecting comment (instruction) in the code.

## HOW TO USE!?

Once the extension is installed, you can select the code you want to get explaination and then righ click and select `Explain` in the menu. 

Alternatively, you can also open `Code-explainer` by clicking the icon and paste the code in the input box.

For code generation, you can select the comment which includes the instruction you want the code to do and then right click to get context menu and select `Generate Code`.

### Explain Code

![Explain code example](https://github.com/xzhaos/VSCodeExplainer/blob/main/assets/codeexplain.gif?raw=true)

### Generate Code

![Generate code example](https://github.com/xzhaos/VSCodeExplainer/blob/main/assets/gencode.gif?raw=true)



### Configuration

But before that, you have to configure your Gemini API key. Go to your VSCode settings(Ctrl + ,) and search for code-explainer and set your `API KEY` which you can easily obtain from here - https://console.cloud.google.com/apis/credentials

### IMPORTANT !!!
> If you want explanation on hover, you can turn on ***Show Explanation on Hover*** (Only compatible with JavaScript) from the settings, but we do not recommend it, since it's in the beta stage.

Here is an example of how the extension can be used:

1. Open a file with some code in it.
2. Select the code you want to explain.
3. Click the `Code Explainer: Explain` command or Open the primary sidebar by clicking the `code-explainer` icon and paste the code in the input box.
4. The extension will generate an explanation for the code and show it in a side panel.

