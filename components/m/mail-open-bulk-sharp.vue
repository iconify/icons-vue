<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="onexarb5h"/><path class="qkaqdetwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.onexarb5h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.555 2.168l9 6A1 1 0 0 1 22 9v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 .445-.832l9-6a1 1 0 0 1 1.11 0");
}

.qkaqdetwr {
  d: path("M9.414 14h5.172l5.707-5.707a.999.999 0 1 1 1.414 1.414l-6 6A1 1 0 0 1 15 16H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
