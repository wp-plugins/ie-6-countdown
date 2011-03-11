=== IE 6 Countdown ===
Contributors: jazzs3quence
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AWM2TG3D4HYQ6
Tags: ie6, internet explorer, browser, microsoft
Requires at least: 2.8
Tested up to: 3.1
Stable tag: 1.0

Help promote a safer internet.

== Description ==

This plugin simplifies participation in Microsoft's campaign to eradicate Internet Explorer 6 from the face of the planet.  There are a lot of plugins that request users in a non-obtrusive (or, in the case of <a href="http://wordpress.org/extend/plugins/upgrade-else-die/">Upgrade Else DIE</a> *very* obtrusive) way, but this one is based on the official Internet Explorer 6 Countdown code available at http://ie6countdown.com/join-us.html.  If you want to be able to participate and use the official upgrade banner, but are unsure how or don't want to mess up your site, this plugin provides an easy and painless way to do so, and isn't that what WordPress is all about?

== Installation ==

1. Upload the zip archive to the `/wp-content/plugins/` directory.
2. Copy and paste the following somewhere into your header.php file (I recommend doing it before the final closing `</div>` of the header, but you can put it wherever looks best for your theme):
`		// put this in your header, or wherever
	&lt;?php do_action('apie6countdown'); ?&gt;`
3. Activate the plugin through the *Plugins* menu in WordPress.
4. That's it!  If you can't see the message, it's working! (Unless you're using IE6, in which case <a href="http://www.microsoft.com/windows/internet-explorer/default.aspx" target="_blank">UPGRADE</a>!

== Screenshots ==

To see what the banner looks like go to http://ie6countdown.com/join-us.html.

== Changelog ==

**Version 1.0.1**

* Fixed the "2 characters of unexpected output" error.

**Version 1.0**

* Created the plugin!

== Upgrade Notice ==

Nothing to see here.