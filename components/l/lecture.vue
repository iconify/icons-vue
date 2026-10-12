<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvj7usbfe"/><circle class="wijmr5spd"/><path class="yt0k09bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lecture" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvj7usbfe {
  d: path("M6.25 11.75h11.5q1.5 0 1.27 1.48l-1.04 6.54q-.23 1.48-1.73 1.48h-8.5q-1.5 0-1.73-1.48l-1.04-6.54q-.23-1.48 1.27-1.48");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.yt0k09bcz {
  d: path("m16.75 11.75l1.5-3.5m-8 8h3.5");
}

</style>
