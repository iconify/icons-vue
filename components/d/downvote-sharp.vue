<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gdl482bha"/><path class="z2a82ccry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:downvote-sharp" /></template>
<style>
.gdl482bha {
  d: path("m13.05 20.17l6.9-7.09L21 12h-5V2.75H8V12H3l1.05 1.08l6.9 7.09L12 21.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2a82ccry {
  d: path("M9.75 8.5L12 10.75l2.25-2.25");
}

</style>
