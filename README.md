# @iconify-vue/ion

**IonIcons**

Author: [Ben Sperry](https://github.com/ionic-team/ionicons)

License: [MIT](https://github.com/ionic-team/ionicons/blob/main/LICENSE)

Browse all icons: [preview IonIcons on Iconify](https://icon-sets.iconify.design/ion/)

## Installation

```bash
npm install github:iconify/icons-vue#ion
```

## Usage

For full documentation visit [Iconify website](https://iconify.design/docs/usage/svg-css/vue/).

Few usage examples:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/ion/code-download-sharp';
</script>
<template>
  <SampleIcon />
</template>
```

To resize icon, set `width` and/or `height` parameters:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/ion/contrast-outline';
</script>
<template>
  <SampleIcon height="1em" />
</template>
```

To change icon color, use style:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/ion/checkmark-done';
</script>
<template>
  <SampleIcon style="color: red;" />
</template>
```
