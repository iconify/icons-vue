<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d3x_iobsj"/><path class="nk9o7tbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clipboard-heart-sharp" /></template>
<style>
.d3x_iobsj {
  d: path("M8.75 4.25h-4v17h14.5v-17h-4");
}

.nk9o7tbxa {
  d: path("M8.75 2.75h6.5v3.5h-6.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
