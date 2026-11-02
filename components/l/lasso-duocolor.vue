<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g481dpbwk"/><path class="yz548cbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lasso-duocolor" /></template>
<style>
.g481dpbwk {
  stroke-opacity: 0.4;
  d: path("M4 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2c0 2 1 4 3 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yz548cbex {
  d: path("M5 12a4.9 4.9 0 0 1-1-3c0-3.314 3.582-6 8-6s8 2.686 8 6s-3.582 6-8 6c-1.45 0-2.757-.44-4-1");
}

</style>
