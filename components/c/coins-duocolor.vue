<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9rhjr-kz"/><path class="t0ppe21yd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coins-duocolor" /></template>
<style>
.j9rhjr-kz {
  stroke-opacity: 0.4;
  d: path("M18 11a5 5 0 1 1-7 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t0ppe21yd {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 0 0 4 9");
}

</style>
