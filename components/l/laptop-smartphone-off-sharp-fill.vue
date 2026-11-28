<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qz2qygb5s"/><path class="xyhuomb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qz2qygb5s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5858 23L13 23C12.4477 23 12 22.5523 12 22L12 12L22.2929 22.2929ZM12.702 9.0451C12.7961 9.0158 12.8962 9 13 9L22 9C22.5523 9 23 9.4477 23 10L23 19.3431Z");
  stroke: none;
}

.xyhuomb6o {
  d: path("M4 14L4 4M6.6569 2L7.6569 2L20 2L20 5M10 18L2 18L2 14L10 14M1.7071 1.7071L22.2929 22.2929");
}

</style>
