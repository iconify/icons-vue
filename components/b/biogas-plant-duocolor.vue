<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xv75rqvyg"/><path class="iw0vpobrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biogas-plant-duocolor" /></template>
<style>
.iw0vpobrp {
  d: path("M3 12v8a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1v-8a6.1 6.1 0 0 0-12 0m0 0h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xv75rqvyg {
  stroke-opacity: 0.4;
  d: path("M9.27 7.006A6.1 6.1 0 0 1 21 8m-8.653 0H21m0 0v8a1 1 0 0 1-1 1h-5");
}

</style>
