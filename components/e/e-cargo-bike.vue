<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u1j3tbbdr"/><path class="sgv56tb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:e-cargo-bike" /></template>
<style>
.sgv56tb5j {
  d: path("M5.5 17.5L9 11h4m5 0v6.5M8.5 3L5.75 6.5h3L6 10");
}

.u1j3tbbdr {
  d: path("M2 17.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm12.5 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM13 4v7h8.5V4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
