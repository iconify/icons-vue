<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h2-5-8b1z"/><path class="cl_x8ccng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magic-wand-ai-sharp" /></template>
<style>
.cl_x8ccng {
  d: path("m5.75 11.25l2.5-2.75l2 2l1.25-1.25l.75.9m5.5 7.6l3.5 3.5m-5-8.25q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25Z");
}

.h2-5-8b1z {
  d: path("M2.75 2.75h11.5v11.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
