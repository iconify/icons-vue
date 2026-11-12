<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y2esomwaf"/><path class="lueqmvvgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent-duocolor-round" /></template>
<style>
.lueqmvvgx {
  d: path("m16 7l3 3c.64.64 1 1.72 1 3v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-4c0-1.28.36-2.36 1-3l4-4a4.243 4.243 0 0 1 6 0z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y2esomwaf {
  stroke-opacity: 0.4;
  d: path("m14 12l-4 4m0-4h.01M14 16h.01");
}

</style>
