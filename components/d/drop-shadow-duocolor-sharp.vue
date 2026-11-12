<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rkx2kcbka"/><path class="d3xxo4y6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drop-shadow-duocolor-sharp" /></template>
<style>
.d3xxo4y6s {
  d: path("M3 3h12v12H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkx2kcbka {
  stroke-opacity: 0.4;
  d: path("M7 21h14V7");
}

</style>
