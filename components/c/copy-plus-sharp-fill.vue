<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kytdc0isv"/><path clip-rule="evenodd" class="cehufz42m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-plus-sharp-fill" /></template>
<style>
.cehufz42m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L22 7C22.5523 7 23 7.4477 23 8L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7ZM14 14L14 11L16 11L16 14L19 14L19 16L16 16L16 19L14 19L14 16L11 16L11 14L14 14Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kytdc0isv {
  d: path("M15.8284 5L15.8284 2L2 2L2 15.8284L5 15.8284");
}

</style>
