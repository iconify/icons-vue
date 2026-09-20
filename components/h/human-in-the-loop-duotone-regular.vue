<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tzdfp4-do"/><path class="l8unaacgj"/><path class="ufzn_r3vk"/><path class="b_e_avbfy"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:human-in-the-loop-duotone-regular" /></template>
<style>
.b_e_avbfy {
  d: path("M7 19a5 5 0 0 1 10 0");
}

.e69i7fcek {
  d: path("M17 12h5");
}

.l8unaacgj {
  d: path("M2 12h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tzdfp4-do {
  fill: currentColor;
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ufzn_r3vk {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
