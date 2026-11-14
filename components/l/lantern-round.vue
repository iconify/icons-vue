<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x44atnbij"/><path class="cx13ds11u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lantern-round" /></template>
<style>
.cx13ds11u {
  d: path("M9 2.5h6V5H9ZM12 18v3.5M4.25 8.75h15.5m-15.5 5.5h15.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x44atnbij {
  d: path("M3.5 11.5a8.5 6.5 0 1 0 17 0a8.5 6.5 0 1 0-17 0Z");
}

</style>
