<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c9wmbmbqf"/><path class="aqxsq5b0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:incognito-duotone-sharp" /></template>
<style>
.aqxsq5b0t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6 10l2-6h8l2 6M3 10h18M4 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-4 0a2 2 0 1 1 4 0");
}

.c9wmbmbqf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.051 3.684A1 1 0 0 1 8 3h8a1 1 0 0 1 .949.684l2 6A1.002 1.002 0 0 1 18 11H6a1.002 1.002 0 0 1-.949-1.316Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
