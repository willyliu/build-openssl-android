# build-openssl-android
Builds openssl library for android. Based on https://github.com/sqlcipher/android-database-sqlcipher/blob/gradle/android-database-sqlcipher/build-openssl-libraries.sh.

## Usage
You must first install Android NDK and then build the openssl library with command like this:

```
ANDROID_NDK_ROOT=/Users/willyliu/Library/Android/sdk/ndk-bundle sh ./build-openssl-android.sh 16 21
```

The first number is the API_LEVEL for 32bit library, and the second number is the API_LEVEL for 64bit library.

The result will be in the `openssl-lib` directory.