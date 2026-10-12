<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lho0jaber"/><path class="gb5ngdcjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-up-left-sharp" /></template>
<style>
.gb5ngdcjv {
  d: path("M8.5 13L4.75 9.25L8.5 5.5");
}

.lho0jaber {
  d: path("M19.75 19.75V9.25h-15");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
