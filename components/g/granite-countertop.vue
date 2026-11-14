<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wdlet2b7w"/><path class="m00hj4ptx"/><path class="utzpsbb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:granite-countertop" /></template>
<style>
.m00hj4ptx {
  d: path("m2.5 11l5-5h14v7l-5 5m0-7l5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utzpsbb1z {
  d: path("M9.75 8.5a2.75 1 0 1 0 5.5 0a2.75 1 0 1 0-5.5 0ZM14 6V3.5h-2.5M5.5 14h.01M9 15.5h.01m3.49-1.75h.01");
}

.wdlet2b7w {
  d: path("M2.5 11h14v7h-14Z");
}

</style>
