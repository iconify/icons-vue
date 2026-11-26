<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ttlcq0vcz"/><path class="h9y5bwbtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h9y5bwbtc {
  d: path("M4 11L4 2L20 2L20 11M19 20L19 22L19 23M5 20L5 22L5 23M2 20L22 20L22 13C22 11.8954 21.1046 11 20 11C18.8954 11 18 11.8954 18 13L18 14L6 14L6 13C6 11.8954 5.1046 11 4 11C2.8954 11 2 11.8954 2 13Z");
}

.ttlcq0vcz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10.1707L3 2C3 1.4477 3.4477 1 4 1L12 1L20 1C20.5523 1 21 1.4477 21 2L21 10.1707C22.1652 10.5825 23 11.6937 23 13L23 20C23 20.5523 22.5523 21 22 21L19 21L12 21L5 21L2 21C1.4477 21 1 20.5523 1 20L1 13C1 11.6937 1.8348 10.5825 3 10.1707Z");
  stroke: none;
}

</style>
