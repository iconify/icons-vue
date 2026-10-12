<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pqoso2jat"/><path class="d3r46qbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:command-palette-sharp" /></template>
<style>
.d3r46qbht {
  d: path("M6.25 5.75L7.75 7l-1.5 1.25M10.75 7h4.5m-9 7.25h11.5");
}

.pqoso2jat {
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 6.5h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
