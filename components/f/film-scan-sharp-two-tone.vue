<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bz8a_bbev"/><path class="o9c24p60m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-scan-sharp-two-tone" /></template>
<style>
.bz8a_bbev {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12V21C14 21.5523 13.5523 22 13 22H3C2.4477 22 2 21.5523 2 21V3C2 2.4477 2.4477 2 3 2H13C13.5523 2 14 2.4477 14 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9c24p60m {
  d: path("M13 21H3V3H13M8 3V21M3 12H13M3 7.5H8M3 16.5H8M13 1V23M17 2V11M17 22V13M21 21V17M21 15V9M21 7V3");
}

</style>
