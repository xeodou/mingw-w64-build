# Automatic build for mingw openssl

[![wercker status](https://app.wercker.com/status/58a778a55c11444226a4dbc2db74b83f/m "wercker status")](https://app.wercker.com/project/bykey/58a778a55c11444226a4dbc2db74b83f)

### Introduction

The repo's branch looks like `1.0.1d` and this refer to the branch `OpeonSSL_1_0_1d` on Openssl here https://github.com/openssl/openssl.

When a branch created at this repo it will automatically trigger a hook an wercker.com, It will automatic build two version openssl library for `i686-w64-mingw32` and `x86_64-w64-mingw32` (i686 is for win32 and x86_64 is for win64/win-amd64).

The binary will upload to https://bintray.com/xeodou/openssl automatically.


### License

MIT
