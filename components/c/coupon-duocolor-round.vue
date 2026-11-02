<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fm0tjs-pa"/><path class="i-1rx4jhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-duocolor-round" /></template>
<style>
.fm0tjs-pa {
  stroke-opacity: 0.4;
  d: path("m14 10l-4 4M9 9h.01M15 15h.01");
}

.i-1rx4jhn {
  d: path("M21 9a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3a3 3 0 0 1 0 6a3 3 0 0 0 3 3h12a3 3 0 0 0 3-3a3 3 0 0 1 0-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
