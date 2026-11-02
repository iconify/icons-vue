<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ax6m2cc8w"/><path class="b9b40_beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-duotone-sharp" /></template>
<style>
.ax6m2cc8w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 15h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1v-4a6.01 6.01 0 0 1 5-5.918V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1.082A6.01 6.01 0 0 1 20 11Z");
}

.b9b40_beb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 16v-5a5 5 0 0 1 5-5m4 0a5 5 0 0 1 5 5v5M3 16h18v4H3Zm7-5V4h4v7");
}

.ft5dv1b6b {
  fill: none;
}

</style>
