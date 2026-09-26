<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ro89z15uz"/><path class="flnna2b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-open-sharp-two-tone" /></template>
<style>
.flnna2b8j {
  d: path("M12 2L2 8.4561L2 22L22 22L22 8.4561L12 2ZM2 10L12 17.1428L22 10");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ro89z15uz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.4576 1.1599L1.4576 7.616C1.1723 7.8002 1 8.1165 1 8.4561L1 22C1 22.5523 1.4477 23 2 23L22 23C22.5523 23 23 22.5523 23 22L23 8.4561C23 8.1165 22.8277 7.8002 22.5424 7.616L12.5424 1.1599C12.2122 0.9467 11.7878 0.9467 11.4576 1.1599Z");
  stroke: none;
}

</style>
