<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ubu-mpbiy"/><path class="uhkypxb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:health-bar-sharp" /></template>
<style>
.ubu-mpbiy {
  d: path("M5.5 16.25s-2.75-2-2.75-4.75a1.6 1.6 0 0 1 2.75-1.1a1.6 1.6 0 0 1 2.75 1.1c0 2.75-2.75 4.75-2.75 4.75Zm5.25-8h10.5v7.5h-10.5z");
}

.uhkypxb0y {
  d: path("M13.25 10.75h4v2.5h-4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
