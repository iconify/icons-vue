<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u-30pfaun"/><path class="w-kv2jb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gauge-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u-30pfaun {
  stroke-opacity: 0.4;
  d: path("m12 13l3-3");
}

.w-kv2jb1n {
  d: path("M6 19a8.485 8.485 0 1 1 12 0");
}

</style>
