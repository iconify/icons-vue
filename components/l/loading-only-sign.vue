<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rh4hqugip"/><path class="m6ewhub8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loading-only-sign" /></template>
<style>
.m6ewhub8q {
  d: path("M8.5 13h7v5h-7ZM12 5v5M9.25 7.25L12 10l2.75-2.75");
}

.rh4hqugip {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
