JPARSEC is a Java Package of Astronomical Resources for Standard Ephemeris Calculations, focused on maximum accuracy and performance, completeness, creation of complex 2D/3D charts, realistic sky and planetary renderings using Java2D, and astrophysical modeling. Latest version adds support for Meade/Celestron telescope control, as well as digital cameras.

The software includes two main parts: the library itself, suitable to develope astronomical programs, and some programs/models already implemented using the JPARSEC library as the common core. Among those programs you will find a planetarium, although the main effort is to the library itself, very useful for the development of the next generation of free planetarium software.

See http://conga.oan.es/~alonso/doku.php?id=jparsec for more information, and http://conga.oan.es/~alonso/doku.php?id=projects to access some projects developed using the JPARSEC library, like a complete online ephemerides server or an applet to explore the sky and planets.

[![](http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=jupitertripleeclipse.png)](http://conga.oan.es/~alonso/doku.php?id=blog:advanced_planetary_rendering)

An example with the triple eclipse in Jupiter on March, 28, 2004, simulated with JPARSEC at the left (pixel by pixel Java2D rendering, no 3d or external libraries). At the right an infrared image taken by the Hubble Space Telescope. The simulation was done with an old version of the library and the textures, with current version image is better. Clic on the image for details.

[![](http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=appletnewversion.png)](http://conga.oan.es/~alonso/doku.php?id=projects#new_sky_and_solar_system_simulator_applet)
<a href='Hidden comment: 
[http://conga.oan.es/~alonso/doku.php?id=blog:mail_name_date_web_service http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=skyhoriz15_3_2011_19_15.png]
'></a>

A rendering of the sky with star and Milky Way textures for high quality, and using English as language. English and Spanish are fully supported.

[![](http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=skyonandroid2.png)](http://conga.oan.es/~alonso/doku.php?id=blog:jparsec_1_9)

Since JPARSEC v1.9 Android platform is also supported with similar features and quality. In the above image an example application is running on the Android 4 emulator. Clic on it for details about the support.

[![](http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=saturnanaglyph.png)](http://www.oan.es/servidorEfem/eindex.php)

JPARSEC contains code to help creating 2d/3d charts with JFreeChart, SGT, Visad, SurfacePlotter, and JMathPlot libraries. In addition, sky and planetary rendering in 3d is supported using different methods, from true 3d output with the left/right eyes view, to the Dubois anaglyph method. Previous image shows Saturn in 3d using the Dubois anaglyph with the red-cyan output mode. These features, combined with the possibility of simulating the sky from other planets, makes possible to combine consecutive images to create very realistic 2d/3d animations/videos. Some examples are available in my blog, for instance at http://conga.oan.es/~alonso/doku.php?id=blog:sky_from_other_planets.

![http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=telescopecontrolpanel.png](http://conga.oan.es/~alonso/lib/exe/fetch.php?w=820&media=telescopecontrolpanel.png)

An on going development is to provide complete telescope and camera control support in JPARSEC (for robotic observatories), including all operations such as the design of observations, their automatic execution, and automatic reduction. Currently some Meade and Celestron models are supported, as well as DSLR cameras (using the gphoto2 project).