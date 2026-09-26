<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ooz35c3wy"/><path class="p2tk3bc2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-plus-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ooz35c3wy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L11 1L11 11L21 11L21 22C21 22.7247 20.2533 23.2087 19.5918 22.9129L12 19.5177L4.4082 22.9129C3.7467 23.2087 3 22.7247 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

.p2tk3bc2p {
  d: path("M20 11L20 22L12 18.4223L4 22L4 2L11 2M17 1L17 9M13 5L21 5");
}

</style>
