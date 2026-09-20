# @iconify-vue/vaadin

**Vaadin Icons**

Author: [Vaadin](https://github.com/vaadin/web-components)

License: Apache 2.0

Browse all icons: [preview Vaadin Icons on Iconify](https://icon-sets.iconify.design/vaadin/)

## Installation

```bash
npm install github:iconify/icons-vue#vaadin
```

## Usage

For full documentation visit [Iconify website](https://iconify.design/docs/usage/svg-css/vue/).

Few usage examples:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/vaadin/area-select';
</script>
<template>
  <SampleIcon />
</template>
```

To resize icon, set `width` and/or `height` parameters:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/vaadin/file-picture';
</script>
<template>
  <SampleIcon height="1em" />
</template>
```

To change icon color, use style:

```vue
<script setup lang="ts">
import SampleIcon from '@iconify-vue/vaadin/plus-circle-o';
</script>
<template>
  <SampleIcon style="color: red;" />
</template>
```
