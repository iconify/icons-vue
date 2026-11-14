<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zox78x7fg"/><path class="ebpfjb2sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floating-stairs" /></template>
<style>
.ebpfjb2sq {
  d: path("M4.375 15.5h2.75A1.375 1.375 0 0 1 8.5 16.875a1.375 1.375 0 0 1-1.375 1.375h-2.75A1.375 1.375 0 0 1 3 16.875A1.375 1.375 0 0 1 4.375 15.5m6.25-5.5h2.75a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-2.75a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 10.625 10m6.25-5.5h3.25A1.375 1.375 0 0 1 21.5 5.875a1.375 1.375 0 0 1-1.375 1.375h-3.25A1.375 1.375 0 0 1 15.5 5.875A1.375 1.375 0 0 1 16.875 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zox78x7fg {
  d: path("M21.5 2.5v19h-19");
}

</style>
