<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="m1nc0tqhq"/><path class="en5inh-5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-sharp-fill" /></template>
<style>
.en5inh-5t {
  d: path("M8 2L8 8M16 2L16 8");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m1nc0tqhq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 4L21 4C21.5523 4 22 4.4477 22 5L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 4.4477 2.4477 4 3 4ZM6 10L18 10L18 12L6 12L6 10Z");
  stroke: none;
}

</style>
