<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h3l_02n5t"/><path class="f2ycr6bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-curve-right-sharp" /></template>
<style>
.f2ycr6bap {
  d: path("m13.25 11.75l4 4l4-4");
}

.h3l_02n5t {
  d: path("M3.75 18.75C3.75 11 7.5 6.5 11.25 6.5s6 4 6 9.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
