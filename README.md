gamethrive-openfl
========================

GameThrive (https://github.com/GameThrive) extension for OpenFL (iOS / Android)

To compile ndlls:

    cd project
    lime rebuild . android
	lime rebuild . ios

Add the extension to haxelib:

    haxelib dev gamethrive-openfl PATH_TO_THE_EXTENSION_ROOT

Usage:

    cd Test
    lime test project.xml android
	lime test project.xml ios

License:

	MIT License
	
TODO:

	Cleaner code...