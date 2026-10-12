<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vizpxnt7h"/><path class="szim-38ur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-grow-sharp" /></template>
<style>
.szim-38ur {
  d: path("M14.25 2.75h4.5v4.5");
}

.vizpxnt7h {
  d: path("M3.75 16.25h3.5v4h-3.5zm6.5-3h3.5v7h-3.5zm6.5-3h3.5v10h-3.5zm-13 1.5l5.5-5.5l3 3l6.5-6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
