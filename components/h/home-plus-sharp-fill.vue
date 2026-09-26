<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zjcrgn3ha"/><path class="ntq22w6oh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-plus-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ntq22w6oh {
  d: path("M19 1L19 9M15 5L23 5");
}

.zjcrgn3ha {
  fill: currentColor;
  d: path("M21 11L20.9998 22.0002C20.9998 22.5525 20.5521 23.0002 19.9998 23.0002L15 23.0002L15 14.0002L7 14.0002L7 23.0002L2.0002 23.0002C1.4479 23.0002 1.0002 22.5525 1.0002 22.0002L1 10.9999C1 10.706 1.1293 10.4269 1.3536 10.2369L10.3881 3.2069C10.7482 2.9266 11.2524 2.9258 11.6135 3.2048L13 4.2856L13 11L21 11Z");
  stroke: none;
}

</style>
