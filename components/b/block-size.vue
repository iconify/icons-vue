<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="efhn3ubkd"/><path class="xg25v1prw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-size" /></template>
<style>
.efhn3ubkd {
  d: path("m12.875 3.005l4.75 2.74a1.75 1.75 0 0 1 .875 1.516v5.228a1.75 1.75 0 0 1-.875 1.516l-4.75 2.74a1.75 1.75 0 0 1-1.75 0l-4.75-2.74a1.75 1.75 0 0 1-.875-1.516V7.261a1.75 1.75 0 0 1 .875-1.516l4.75-2.74a1.75 1.75 0 0 1 1.75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg25v1prw {
  d: path("M5.5 6.25L12 10l6.5-3.75M12 10v7.25M4.5 20.5h15M6 19l-1.5 1.5L6 22m12-3l1.5 1.5L18 22");
}

</style>
