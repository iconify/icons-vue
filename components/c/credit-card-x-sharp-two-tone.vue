<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pi2qqqb_t"/><path class="ulr3o7bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-x-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi2qqqb_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 10C23 10.5523 22.5523 11 22 11L13 11L13 20C13 20.5523 12.5523 21 12 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.ulr3o7bai {
  d: path("M22 10L22 9L22 4L2 4L2 20L12 20L13 20M1 9L2 9L22 9L23 9M16 14L22 20M22 14L16 20");
}

</style>
