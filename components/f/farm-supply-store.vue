<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n2jh8ls7s"/><path class="sbv6bfbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-supply-store" /></template>
<style>
.n2jh8ls7s {
  d: path("m3.5 11l3-5.5L12 3l5.5 2.5l3 5.5v10h-17Z");
}

.sbv6bfbfo {
  d: path("M9 9v2a3 3 0 0 0 6 0V9m-3 0v9.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
