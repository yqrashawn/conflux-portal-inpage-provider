# ConfluxPortal Inpage Provider

Used to initialize the inpage ethereum provider injected by ConfluxPortal.

## Installation

`yarn add @yqrashawn/conflux-portal-inpage-provider`

## Usage

```javascript
// Create a stream to a remote provider:
var confluxPortalStream = new LocalMessageDuplexStream({
  name: 'inpage',
  target: 'contentscript',
})

// compose the inpage provider
var inpageProvider = new ConfluxPortalInpageProvider(confluxPortalStream)
```
