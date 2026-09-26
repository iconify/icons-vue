<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qd-pmp7al"/><path class="rl_3hqbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qd-pmp7al {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 22C21 22.7247 20.2533 23.2087 19.5918 22.9129L12 19.5177L4.4082 22.9129C3.7467 23.2087 3 22.7247 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

.rl_3hqbmk {
  d: path("M4 2L20 2L20 22L12 18.4223L4 22L4 2Z");
}

</style>
