The PureNexus Project
=====================

Getting Started
---------------

To build PureNexus from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/xorware/manifest.git -b n

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default

Enjoy, Stick around for a while AOSP Building is Fun!!!

[@BeansTown106](https://twitter.com/beanstown106) on Twitter

[PureNexus Community](https://plus.google.com/u/0/communities/103055954354785266764) on Google+

[PureNexusProject-Legacy](https://github.com/PureNexusProject-Legacy) Old Source and Reference code
