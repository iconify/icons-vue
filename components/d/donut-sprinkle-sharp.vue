<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zwktpqbzq"/><path class="o-kdnipuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donut-sprinkle-sharp" /></template>
<style>
.o-kdnipuu {
  d: path("M8.5 10.25a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0ZM3.5 14l1.414 1.571L6.25 14c.75 1.75 2.25 1.75 3 0l1.671 1.857L12.5 14c.75 1.75 2.25 1.75 3 0l1.414 1.571L18.25 14m-12-4l1-.5m1-2L9 8m6.75-.5L15 8m2 1.75l.75.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwktpqbzq {
  d: path("M3.25 11c0-3 3.9-5.25 8.75-5.25S20.75 8 20.75 11v2.5c0 3-3.9 5.25-8.75 5.25S3.25 16.5 3.25 13.5Z");
}

</style>
