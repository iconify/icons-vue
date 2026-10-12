<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dxlzgxf7a"/><path class="iyxto8b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bed-and-breakfast-sharp" /></template>
<style>
.dxlzgxf7a {
  d: path("M3 10.75v10.5M3 14h18.25v4.25H3zm16.75 4.25v3M5.5 11h5v3h-5zm6.75-6h6v3a3 3 0 0 1-6 0Z");
}

.iyxto8b-j {
  d: path("M18.25 5.75h2.5v3.5H18.1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
