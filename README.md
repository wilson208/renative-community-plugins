![npm](https://img.shields.io/npm/v/renative-community-plugins?style=for-the-badge)

# renative-community-plugins

## Usage

### Add `community` PLugin Source
`renative.json`
```json
{
  "pluginTemplates": {
    "community": {
      "npm": "renative-community-plugins",
      "path": "./pluginTemplates"
    }
  }
}
```

### Add `community` Plugins Source
`renative.json`
```json
{
  "plugins": {
    "@react-navigation": "source:community"
  }
}
```

## Available Plugins

- `@react-navigation`
- `native-base`
- `react-native-fast-image`
- `react-native-screens`
- `react-native-safe-area-context`
- `@react-native-community/masked-view`
- `@react-aria/focus`
- `@react-aria/utils`
- `@react-aria/visually-hidden`
- `@react-native-aria/button`
- `@react-native-aria/checkbox`
- `@react-native-aria/combobox`
- `@react-native-aria/focus`
- `@react-native-aria/interactions`
- `@react-native-aria/listbox`
- `@react-native-aria/overlays`
- `@react-native-aria/radio`
- `@react-native-aria/slider`
- `@react-native-aria/tabs`
- `@react-native-aria/utils`
