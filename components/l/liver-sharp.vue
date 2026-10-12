<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o3veqpbbf"/><path class="rcpixv49p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:liver-sharp" /></template>
<style>
.o3veqpbbf {
  d: path("M3 8.5c0-2 1.5-3.25 3.5-3.25c4 0 9.5-1.5 12.5-1.5c1.75 0 2.25 1.5 2 3c-.75 4.75-5 9.75-10.5 11.5c-1.5.5-2.5-.5-2.75-2C9 13 3 13 3 8.5Z");
}

.rcpixv49p {
  d: path("M13.5 4.5c-.75 3-2 5.5-4 7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
