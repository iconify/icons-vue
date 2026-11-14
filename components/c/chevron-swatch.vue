<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="p5zvfc-vg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chevron-swatch" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.p5zvfc-vg {
  d: path("m3 6.75l4.5 4l4.5-4l4.5 4l4.5-4m-18 6.5l4.5 4l4.5-4l4.5 4l4.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
