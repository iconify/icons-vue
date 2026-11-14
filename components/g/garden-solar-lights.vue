<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="chgibj8pa"/><path class="h5fovibvw"/><path class="r2yndgt2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-solar-lights" /></template>
<style>
.chgibj8pa {
  d: path("M4.5 2.5h15l2 6.5h-19ZM12 12v9.5m-2.5-19L8.75 9m5.75-6.5l.75 6.5");
}

.h5fovibvw {
  fill: currentColor;
  d: path("M10 9h4v3h-4Z");
}

.r2yndgt2i {
  d: path("M7.25 12.25L5.5 14.5m11.25-2.25l1.75 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
