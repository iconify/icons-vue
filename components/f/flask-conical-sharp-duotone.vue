<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tvbb9gb-d"/><path class="r1a_d_bgc"/><path class="dx93_50hj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-sharp-duotone" /></template>
<style>
.dx93_50hj {
  d: path("M7 2L17 2");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1a_d_bgc {
  fill: currentColor;
  d: path("M4.8899 17L19.1101 17L20.9307 21.6344C20.9765 21.7508 20.9999 21.8749 20.9999 22C20.9999 22.5523 20.5522 23 19.9999 23L4.0001 23C3.4478 23 3.0001 22.5523 3.0001 22C3.0001 21.8749 3.0235 21.7508 3.0693 21.6344Z");
  stroke: none;
}

.tvbb9gb-d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.5 1L14.5 1C15.0523 1 15.5 1.4477 15.5 2L15.5 7.8106L20.9307 21.6344C20.9765 21.7508 20.9999 21.8749 20.9999 22C20.9999 22.5523 20.5522 23 19.9999 23L4.0001 23C3.4478 23 3.0001 22.5523 3.0001 22C3.0001 21.8749 3.0235 21.7508 3.0693 21.6344L8.5 7.8106L8.5 2C8.5 1.4477 8.9477 1 9.5 1Z");
  stroke: none;
}

</style>
