[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/2.0.0/active.svg)](https://github.com/xoopscube/xcl)
![License GPL](https://img.shields.io/badge/License-GPL-green)
![X-Updare Store](https://img.shields.io/badge/X--Update%20Store-Pending-red)

## ///// — XOOPSCUBE THEMES


---

GitHub | [XOOPSCUBE-THEMES](https://github.com/xoopscube-themes)  
------------ | -------------
Description | Starter Themes built with different CSS Frameworks
Render Engine | Smarty v2 and Smarty v3
Version | 2.3.1
Copyright | 2011-2022 Authors
License | Misc.


##### :computer: The Minimum Requirements



          Apache, Nginx, etc. PHP 7.2.x
          MySQL 5.6, MariaDB  InnoDB utf8 / utf8mb4
          XCL version >= 2.3.1



-----


## Overview   

The XOOPSCUBE legacy renderer was designed for backwards compatibility with XOOPS2 and XOOPS2-JP legacy themes.    
The Renderer uses Smarty Template Engine — one of the most popular and mature template engines.

Smarty is a template engine for PHP. More specifically, it facilitates a manageable way to separate application logic and content from its presentation.
This is best described in a situation where the application programmer and the template designer play different roles.   
Smarty Template Engine is used for rendering and cache management, it has neither override nor fall-back mechanism.

## Themes and Templates

The Theme specifies the areas and appearance, and the module template specifies the shape. 

Themes and modules Templates are built with HTML, CSS, JavaScript and Smarty tags    
— Smarty is used with custom delimiters <{ ... }> very similar to HTML markup language that make it easier to design and develop components.

The block "side"" is just a legacy code convention to identify areas in the theme and organize the layout. Blocks are modular units of content that can be positioned almost anywhere on the page. For example, a theme can place the block-left "Main Menu" at the top of the page to create a navigation bar.

## Template Management 

The Renderer features a **Template Management** to enable a **Template Set** and check the **list of templates** that you can edit, copy, download or delete. Its user-friendly GUI allows you to manage files more easily, even when they’re not all stored in one central folder or directory.   
Although, some Themes have a template directory including most, if not all template files to meet an organization's needs for customization and personalization.

**Learn more about Smarty**    
[What is Smarty v2](https://www.smarty.net/docsv2/en/what.is.smarty.tpl)    
[Smarty 3 Overview](https://www.smarty.net/v3_overview)    


### Features


- Grid & Flexbox layout
- Responsive themes
- CSS Custom properties
- Localization    


### Install or Update Themes

1. Select a branch from this repo and, from the dropdown button "Code" select Clone or Download zip.  
2. Extract and upload the folder "theme-name" to your domain, eg.: public/html/themes/theme-name/*.*  
3. Login to your the Administration Control Panel » Theme Management, activate the Theme (select).  

### User-friendly installation

**X-Update Store**  

1. Login to your the Administration Control Panel » X-Update » Themes    
2. Select the theme from the Theme Store    
3. Proceed to automatically download and install.

    

## Feature Branch Workflow

Branches are used to build independent Themes, Templates, Components and features.  
Following the core idea behind the **Feature Branch Workflow** each theme development   
takes place in a dedicated branch instead of the main branch. This encapsulation makes   
it easy for multiple themes built with a specific CSS framework or xLayout.

### 1 - Clone the repository   

You can clone the repository to create a local copy on your computer.  
This gives us access to all branches in this repository.

``` 
git clone https://github.com/xoopscube-themes/xcl-html5-boilerplate.git
```

> When you clone a repository, you get the **main** branch by default.   
> This means you will have to checkout another branch yourself.   
> You can easily switch between each branch using GitHub Desktop.  



### 2 - Clone a Specific Branch

There are two ways to clone a specific branch. You can either:

a) Clone the repository, fetch all branches, and checkout a specific branch.
b) Clone the repository and fetch only a single branch.  

#### Option One  

``` 
git clone --branch <branchname> <remote-repo-url>
```

or using **-b** an alias for --branch

``` 
git clone -b <branchname> <remote-repo-url>
``` 

#### Option Two

``` 
git clone --branch <branch-theme-name> --single-branch <remote-repo-url>
``` 

or using **-b** an alias for --branch

``` 
git clone -b <branch-theme-name> --single-branch <remote-repo-url>
``` 

> This performs the same action as option one, except that the **--single-branch** option   
> only fetch the files from the specified Theme branch without fetching other branches.


**Learn more...**   
  
- [Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)  
- [GitHub - Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)  




#### Theme Folder Structure

Technically, themes only require four files : manifesto.ini.php, screenshot.png, style.css, theme.html.   
You can create a folder **assets** for all the assets used in the theme, including images, stylesheets, and javascript files.    
The following is an example of the files and folders that can be found in typical XCL theme folder structure.</p>
        
```bash
themes
└───theme-name
    │   CHANGELOG.md
    │   manifesto.ini.php
    │   README.md
    │   screenshot.png
    │   theme.html
    │
    ├───component
    ├───css
    ├───images
    ├───js
    ├───language
    └───templates
        ├───d3forum
        ├───legacy
        ├───legacyRender
        ├───message
        ├───pico
        ├───profile
        └───user
```


License
-------

The Themes are released under a BSD or Creative Commons license.  
Some Components and Plugins can be released under licenses that   
guarantee a certain specific set of freedoms - GPL, MIT, etc.  

[LICENSE](LICENSE)

Code contributions
----------------

If find a bug or it's a feature that you think should be implemented [please open an issue first](https://github.com/xoopscube-themes/xcl-html5-boilerplate/issues),   
join or start a [new discussion](https://github.com/orgs/xoopscube-themes/discussions).    

Otherwise, you can follow this process:

1. Fork the project [Fork a Repo](http://help.github.com/fork-a-repo/)
2. Create a feature branch : `git checkout -b my_branch`
3. Push your changes to your new branch : `git push origin my_branch`
4. Initiate a pull request [About Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
5. Your pull request will be reviewed and hopefully merged :)

Have Fun ^_^/

  
  
-----  

<h3 align="center">Big Thanks</h3>    
  
<p align="center"><a href="https://www.jetbrains.com/" target="_blank">JetBrains</a> is an active participant in the <a href="https://jetbrains.com/opensource/" target="_blank">Open Source</a>.<br>
Big thanks to the JetBrains Team for their support ^_^/ </p>
  
<p align=center><img src="https://raw.githubusercontent.com/xoopscube/artwork-social-media/master/logo/jetbrains-logo-variant-3-256.png" alt="Big thanks to the JetBrains Team for supporting XOOPSCube Project" title="Big thanks to the JetBrains Team" /></p>
  
-----

