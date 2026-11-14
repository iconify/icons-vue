<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v3zj1hyoq"/><path class="kymwa3yvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-repair-garage" /></template>
<style>
.kymwa3yvj {
  d: path("M6 19.5V12h6.5v7.1M6 15.5h6.5m6.75-1.75a2.5 2.5 0 1 0 2.5 2.5M17.5 18l-2.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3zj1hyoq {
  d: path("M3 19.5V9l8.75-5.5L20.5 9v1.93");
}

</style>
