# Smooth Level Enter — GD 2.2074 unofficial port

Rollback/stable test source. This intentionally keeps the upstream transition lifecycle unchanged because the previous background-fix experiment stopped the transition entirely on 2.2074.

Changes from upstream are deliberately minimal:
- Geode 4.10.2 / GD 2.2074 metadata.
- Node IDs v1.21.0 for the 2.2074 setup.
- C++20.
- `std::mt19937` replacement for the Geode 5 random helper.
- CI targets Windows, Android32 and Android64 only.

Known remaining issue: the core smooth transition works, but background behavior still needs a separate 2.2074-specific fix.
