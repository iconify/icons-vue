<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vqyt1wbnn"/><path class="p0quvab7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-text-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p0quvab7v {
  d: path("M19 10h-4a3 3 0 0 1-3-3V3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10m-5-3a.997.997 0 0 0 1 1h1.586L14 5.414Zm1 8H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2m0 4H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

.vqyt1wbnn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
