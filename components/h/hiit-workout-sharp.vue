<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a0i1yybpz"/><path class="rcgf06bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hiit-workout-sharp" /></template>
<style>
.a0i1yybpz {
  d: path("M3.75 13a8.25 8.25 0 1 0 16.5 0a8.25 8.25 0 1 0-16.5 0M10 2.75h4m-2 0v2");
}

.rcgf06bjs {
  d: path("m12.95 8.4l-3.9 5.2l-.3.4H12l-.15.48l-.95 3.04l-.15.48l.3-.4l3.9-5.2l.3-.4H12l.15-.48l.95-3.04l.15-.48z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
