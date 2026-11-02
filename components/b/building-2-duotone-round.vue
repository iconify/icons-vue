<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ao-7xzujy"/><path class="xgdo7q_mf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-duotone-round" /></template>
<style>
.ao-7xzujy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21a1 1 0 0 1-1-1V7a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4v13a1 1 0 0 1-1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.xgdo7q_mf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18m-9 0V7a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3v13m7-9a2.83 2.83 0 0 1 4 0l2 2c.64.64 1 1.72 1 3v4");
}

</style>
