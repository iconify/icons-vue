<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kiiqxz0tg"/><path class="y1fe95b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beehive-sharp" /></template>
<style>
.kiiqxz0tg {
  d: path("M4.25 21.25V19L5 16.75c1-7.5 3.5-12 7-12s6 4.5 7 12l.75 2.25v2.25Zm2.65-12h10.2M5.68 13h12.64M10 16.75H5m9 0h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1fe95b1p {
  d: path("M10.25 21.25V18.5h3.5v2.75");
}

</style>
