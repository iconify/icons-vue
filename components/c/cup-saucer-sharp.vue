<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="frrxzxbga"/><path class="g7xyxzbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cup-saucer-sharp" /></template>
<style>
.frrxzxbga {
  d: path("M4.25 5h11.5v4.75a5.75 5.75 0 0 1-11.5 0Z");
}

.g7xyxzbef {
  d: path("M15.75 6.75h1.75a2.5 2.5 0 0 1 0 5h-2.25M2.75 18.5h18.5l-1.179 2.75H3.929z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
