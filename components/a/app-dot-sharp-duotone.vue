<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i2koj3lau"/><path class="q_l1jacog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-dot-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i2koj3lau {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2L3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22L21 22C21.5523 22 22 21.5523 22 21L22 14C22 13.4477 21.5523 13 21 13L11 13L11 3C11 2.4477 10.5523 2 10 2Z");
  stroke: none;
}

.q_l1jacog {
  d: path("M18 3C19.6568 3 21 4.3432 21 6C21 7.6569 19.6568 9 18 9C16.3432 9 15 7.6569 15 6C15 4.3432 16.3432 3 18 3Z");
}

</style>
