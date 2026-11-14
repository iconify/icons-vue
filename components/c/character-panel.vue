<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b27-yrh8j"/><path class="m2nmvobxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:character-panel" /></template>
<style>
.b27-yrh8j {
  d: path("M3 3h18v18H3Zm0 4.5h18");
}

.m2nmvobxf {
  d: path("m6 18l3-7.5l3 7.5Zm1-2.5h4m4-3.5h3m-3 4h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
