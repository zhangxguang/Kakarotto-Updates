# Kakarotto Updates

This public repository hosts the signed update feed and notarized macOS release
artifacts for Kakarotto. It does not contain the Kakarotto source code or any
update-signing private keys.

- Update feed: <https://zhangxguang.github.io/Kakarotto-Updates/appcast.xml>
- Releases: <https://github.com/zhangxguang/Kakarotto-Updates/releases>

Kakarotto verifies every update with Sparkle EdDSA signatures, Developer ID
code signing, and Apple's notarization checks before installation.
