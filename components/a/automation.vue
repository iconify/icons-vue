<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="goxjtemri"/><path class="cclh0-b1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation" /></template>
<style>
.cclh0-b1r {
  d: path("M17.5 2.5L20 5l-2.5 2.5M2.75 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.goxjtemri {
  d: path("M6.75 19H14a3.5 3.5 0 0 0 0-7h-4a3.5 3.5 0 0 1 0-7h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
