<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s57e7z62g"/><path class="zokx3-ymx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:charger-sharp" /></template>
<style>
.s57e7z62g {
  d: path("M5.75 7.25h12.5v9.5H5.75zm3.75-4.5v4.5m5-4.5v4.5m-2.5 9.5v4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zokx3-ymx {
  d: path("m12.75 9.5l-2 2.75h2.5l-2 2.5");
}

</style>
