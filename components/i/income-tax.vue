<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irbrwkyut"/><path class="qrqgcbcrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:income-tax" /></template>
<style>
.irbrwkyut {
  d: path("M13.6 16H2.5V4h18v7.7");
}

.qrqgcbcrf {
  d: path("M9 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm9 4.5v7m-3-3l3 3l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
