<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cxpfe8woi"/><path class="bt23kfbkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:framer-bulk-sharp" /></template>
<style>
.bt23kfbkz {
  d: path("M6 2h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-6a1 1 0 0 1-.707-.293l-6-6A1 1 0 0 1 6 2m11 6V4H8.414l4 4ZM6 14h6a1 1 0 0 1 1 1v6a1.002 1.002 0 0 1-1.707.707l-6-6A1 1 0 0 1 6 14m5 4.586V16H8.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.cxpfe8woi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 18 16H6a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
