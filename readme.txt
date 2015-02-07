=== Sign Me Up ===
Contributors: jaromy
Donate link: http://www.jaromy.net/wordpress-plugins/donate/
Tags: phplist, ajax, form, signup, signup form, mailing list, subscription, widget 
Requires at least: 4.0.0
Tested up to: 4.1.0
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


Add a simple straightforward sign-up form to your WordPress site. Integrates with phpList, the most popular open-source newsletter manager.


== Description ==

= Sign Me Up =

This plugin is a widget that adds a simple sign-up form to your WordPress site, allowing visitors to subscribe to your mailing list. It serves as a front end to [phpList](http://www.phplist.com), the most popular open-source newsletter manager (over 1.5 million downloads according to their website). The widget connects to phpList via AJAX, which allows a visitor to subscribe without leaving your WordPress page - no refresh or redirect is necessary. 

**Features:**

* Add a simple "sign-up to our newsletter" form to your WordPress site
* Provides a back-end connection to the powerful open-source mailing list manager, phpList 
* Maintains the consistent look, feel, and branding of your WordPress site
* Uses AJAX – no page refresh or redirects. Status & feedback are displayed on the same page as the form
* Minimal, elegant, simple. Seamlessly blends in with your theme by incorporating existing styling rules
* Easy customization – change the text of each form element so it says exactly what you want
* Widgetized – easily add it to your site via drag & drop
* Error checking – client side validation via popular jQuery Validation library provides immediate feedback to the user and reduces erroneous data

**More information**

* [Sign Me Up](http://www.jaromy.net/wordpress-plugins/sign-me-up/)

== Installation ==

To install this plugin:

1. Upload the contents of sign-me-up.zip to your plugins directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the Sign Me Up widget to your site using the Appearance -> Widgets menu.
1. Specify your form settings in the widget. For more info head over to: [Sign Me Up](http://www.jaromy.net/wordpress-plugins/sign-me-up/)
1. That's all. You're done!

Alternatively you can search for the plugin from your WordPress dashboard and install from there.

== Frequently Asked Questions ==

= Do I need to use phpList? =

Yes, this plugin specifically designed to use phpList as the mailing list manager to store the email adresses

= Will it work with other mailing list services such as MailChimp? =

No, this plugin will not work with MailChimp or other mailing list services. It is designed as a free open-source alternative to these paid services. So, instead it works with phpList.

= Can I add additional fields for the user to fill out, such as Name? =

Unfortunately, no. Currently there is no provision in the AJAX code in phpList to parse these additional parameters. As a workaround,
it is possible to request for these fields (Name, Zip Code, etc) in any of the confirmation emails sent by phpList, or have
the user update their profile with these additional details.

= Can I use more than one Sign Me Up widget? =
 
You can only have one widget per WordPress page. But, you can setup multiple widgets that each reside on a different page of your website. For example, one widget on the "Contact Us" page, a different widget on the "Latest News" page, etc. This allows you to customize the message of the signup form to whatever content you are displaying on that page.

= How do I customize the response message? =

The messages for a successful response can be customized via the Subscribe Page in phpList. Unfortunately, the error messages and failed submission messages cannot be customized.



== Screenshots ==

1. Example of the form on a Wordpress page. Elegant, simple, and minimal. Place it anywhere you want via the Wordpress Widgets admin page.
2. Built-in error checking - ensures email follows a valid format and reduces typographical errors. 
3. Example form, after a successful submission. Message and formatting is configured via phpList Subscribe Page.
4. Configuring the form via Wordpress admin backend. Use the widgets control panel to access and configure the plugin.
5. Default signup list form provided by phpList. It's a separate page that does not have the same look & branding as your Wordpress site.
6. Subscribe Pages configuration area in phpList.
7. Subscribe page configuration in phpList - 1) Customize the confirmation message, 2) Radio checkbox settings 
8. Subscribe page configuration in phpList - associate list with this page/signup form


== Changelog ==

= 1.0 =
* Initial release

= 1.1 =
* Screenshots added
* Fixed incorrect name in readme file

== Upgrade Notice ==

= 1.0 =
Initial release

= 1.1 = 
Cosmetic fixes for plugin page on wordpress.org
