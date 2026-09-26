<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tvbb9gb-d"/><path class="klg4_yvwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.klg4_yvwp {
  d: path("M9.5 2L14.5 2L14.5 8L19.9999 22L4.0001 22L9.5 8L9.5 2ZM7 2L17 2M5.5715 18L18.4285 18");
}

.tvbb9gb-d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.5 1L14.5 1C15.0523 1 15.5 1.4477 15.5 2L15.5 7.8106L20.9307 21.6344C20.9765 21.7508 20.9999 21.8749 20.9999 22C20.9999 22.5523 20.5522 23 19.9999 23L4.0001 23C3.4478 23 3.0001 22.5523 3.0001 22C3.0001 21.8749 3.0235 21.7508 3.0693 21.6344L8.5 7.8106L8.5 2C8.5 1.4477 8.9477 1 9.5 1Z");
  stroke: none;
}

</style>
