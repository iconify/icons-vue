<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="avs7pybtk"/><path class="bwqn15byx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loafer" /></template>
<style>
.avs7pybtk {
  d: path("M2.5 17.5v-10l5 2l4-3q6.5 1 9 5.25q1 1.75 1 3.5v2.25Zm0-2.25h19");
}

.bwqn15byx {
  d: path("M10.25 7.5Q13.5 12 17 8.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
