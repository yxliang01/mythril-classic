# Analysis results for test-filename.sol

## Use of tx.origin
- SWC ID: 111
- Severity: Medium
- Contract: Unknown
- Function name: `transferOwnership(address)`
- PC address: 317
- Estimated Gas Usage: 626 - 1051

### Description

Use of tx.origin is deprecated.
The smart contract retrieves the transaction origin (tx.origin) using msg.origin. Use of msg.origin is deprecated and the instruction may be removed in the  future. Use msg.sender instead.
See also: https://solidity.readthedocs.io/en/develop/security-considerations.html#tx-origin
