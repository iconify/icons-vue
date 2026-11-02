<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qxkwt7b5y"/><path class="wdeud0bza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-euro-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qxkwt7b5y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 9h6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 4h6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

.wdeud0bza {
  d: path("M16.285 6.373a6.072 6.072 0 1 0 2.008 9.92a.999.999 0 1 1 1.414 1.414a8 8 0 0 1-2.67 1.773a8 8 0 0 1-3.037.591a8.073 8.073 0 1 1 5.707-13.778a.999.999 0 1 1-1.414 1.414a6 6 0 0 0-2.008-1.334");
}

</style>
