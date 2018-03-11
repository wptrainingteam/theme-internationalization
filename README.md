# Theme Internationalization

Over 60 million people have chosen WordPress to power the place on the web they call “home”. People from all over the word create WordPress sites in different languages. While WordPress has translations for over 162 languages, you will be only able to see languages that are fully translated (62). If you do not see your language in the list, this does not mean that it is not available or that you cannot use it.

## Description

In this training you will learn how to install WordPress in a language other than English, how you can change the language after installation, and also how to change the wp-admin language per user. We will also learn how to find a theme in the theme directory in the local language and which also supports RTL (Right To Left) languages.

## Prerequisite Skills

*   Know how to install a theme
*   Know how to create users

## Objectives

After this lesson, students will be able to:

*   Install WordPress in a language other than English.
*   Change the WordPress language after they have installed the site.
*   Change the wp-admin language, per user (4.7 feature).
*   Choose a theme from the theme directory which supports their local language.
*   Choose a theme which supports RTL languages.

## Assets

Files/materials the instructor will need to teach this lesson:

*   An installed WordPress site.

## Screening Questions

*   Have you ever installed a new WordPress site?
*   Have you ever created new users on a WordPress site?

## Teacher Notes

A bulleted list of any handy tips or information for the instructor.

*   Tips teachers may want to know

## Hands-on Walkthrough

These are the steps for creating WordPress in your own language:

1.  Start the famous "5 minute install"
2.  During the installation process you will have the option to select your language via this screen: Selecting this language will set the language for the "Front end" of your website and also for the "Back end" - the wp-admin sometimes also called the dashboard.

[![](https://make.wordpress.org/training/files/2014/10/Wordpress-Choose-Language-Installation.jpeg)](https://make.wordpress.org/training/files/2014/10/Wordpress-Choose-Language-Installation.jpeg)   Continue with the installation process and soon you will have a WordPress install in the language you selected. **I have already installed a site in English - can I change it to a different language?** Fortunately, yes you can! This can easily be done by navigating to: Settings > General and then changing the language in the "Site Language" [![](https://make.wordpress.org/training/files/2014/10/WordPress-Site-Language.png)](https://make.wordpress.org/training/files/2014/10/WordPress-Site-Language.png)

### Changing only the wp-admin language

There are situations where the site is installed in one language, but  a user in your site (an Author or Editor) would like to edit the site in a different one. This is a new feature in version 4.7 and can be done by accessing a user's profile and changing the admin to a different language. [![](https://make.wordpress.org/training/files/2014/10/adminlocale.jpg)](https://make.wordpress.org/training/files/2014/10/adminlocale.jpg)

## Internationalizing a Theme

If you would like to create a website in your own language, chances are there is a theme translated to that language. If your language is RTL (Arabic, Hebrew, Persian etc...), you would also want to install a theme which supports RTL. Wordpress has thousands of themes to choose from, either from the [theme directory](https://wordpress.org/themes/) on wordpress.org or from other theme merchants on the web. When choosing a theme for use in a language other than English, we should take in account for 2 major items:

1.  Is the theme translated to the local language?
2.  Does the theme have an RTL CSS file - for languages which are RTL - Hebrew, Arabic, Persian etc...?

## Is the theme translated to my local language

When selecting a new theme from the [WordPress theme directory](https://wordpress.org/themes/)  click on the "More Info" button. On the The's information page you can see in the sidebar a link to the theme's translation page. ![More info theme select](https://make.wordpress.org/training/files/2014/10/more-info-theme.jpg) In that page you can see if the theme has been translated to other languages and how much progress has been made for each language. Let's look at the twentysixteen theme. In the [Theme's page](https://wordpress.org/themes/twentysixteen/) in the directory we can see a link to "Translations" [![](https://make.wordpress.org/training/files/2014/10/theme-translation.jpg)](https://make.wordpress.org/training/files/2014/10/theme-translation.jpg) Clicking that link will bring us to the translations page of that theme where we can see the progress of all the translations available for this theme. If we see a Language which is not 100% and we would like to translate , it can easily be done by clicking on the language, and from there translate the strings that are in need for translating. [![](https://make.wordpress.org/training/files/2014/10/translate.jpg)](https://make.wordpress.org/training/files/2014/10/translate.jpg) WordPress theme tranlations are centralized and can be accessed via [https://translate.wordpress.org](https://translate.wordpress.org)

## Does the theme have an RTL CSS file

When looking for themes, we have a filter option in the themes' directory which will allow us to fine tune a selection of themes to our needs. One of these options is selecting a theme with support to RTL languages. RTL languages need support for RTL themes in order to display their content correctly. [![Features Filter](https://make.wordpress.org/training/files/2014/10/features-filter.jpg)](https://make.wordpress.org/training/files/2014/10/features-filter.jpg) Clicking on the Features Filter button will bring up various features for selecting from the themes. One of those features is selecting RTL support. [![RTL Language Support Checkbox](https://make.wordpress.org/training/files/2014/10/rtl-language-support.png)](https://make.wordpress.org/training/files/2014/10/rtl-language-support.png) Checking that checkbox and then clicking the button "Apply Filters" on the top of the page, will display themes which support RTL layout (and any other filter that has been selected). [![Theme RTL Filter](https://make.wordpress.org/training/files/2014/10/themes-rtl-filter.png)](https://make.wordpress.org/training/files/2014/10/themes-rtl-filter.png) This would be a good starting point for creating your RTL website.

## Exercises

**Change the language of your WordPress install** After installing WordPress, go to the wp-admin and change it to a different language. **Create a new user and change his language to a different than the one installed.** **Select a theme from the theme direcory which supports RTL and has a left sidebar.**

## Quiz

A short quiz for students to evaluate their retention of the material presented. **How are WordPress themes translated.**

1.  A language file inside the theme's folder
2.  In the theme's code
3.  Centralized, via wordpress.org website
4.  Themes are not translated

**Answer:** 3\. Correct answer **Do themes support RTL languages?**

1.  No, You would have to code it yourself
2.  Yes, you can find RTL supported themes in the theme directory.
3.  Why would I need a theme for?

**Answer:** 2\. Correct answer **Can you change the installation language of WordPress?**

1.  No, you would have to reinstall WordPress again
2.  You can only change the usr's wp-admin language, not the install language
3.  Yes, you can always change the WordPress language through the settings menu.

**Answer:** 3\. Correct answer
