## [1.3] - 2025-09-15

### Added
- `server/webhook.lua` for Discord notifications. Set your Discord webhook URL (leave as `''` to disable).

### Fixed
- Target and light settings now persist after server restarts and when a prop is placed while other players are outside the culling radius.

### Performance
- Improved optimization near light props; `resmon` now reports `0.00` when you’re outside the detection radius.

### TODO
- Replace radius detection with PolyZone-based detection.
