# manifest

Cold Fusion AOSP ROM

repo init -u https://github.com/zopozop/manifest.git -b mm6.0.1

repo sync

source build/envsetup.sh

lunch

make -j16 otapackage
