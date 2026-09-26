<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="b3w-c-s0b"/><path class="dt67b79cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-check-sharp-fill" /></template>
<style>
.b3w-c-s0b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 4L21 4C21.5523 4 22 4.4477 22 5L22 11C22 11.5523 21.5523 12 21 12L12 12L12 21C12 21.5523 11.5523 22 11 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 4.4477 2.4477 4 3 4ZM6 10L18 10L18 12L6 12L6 10Z");
  stroke: none;
}

.dt67b79cb {
  d: path("M8 2L8 8M16 2L16 8M14.7071 17.7071L17 20L21.2929 15.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
