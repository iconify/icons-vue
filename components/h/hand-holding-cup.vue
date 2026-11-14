<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxtnnnblw"/><path class="gjnnl7s9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-holding-cup" /></template>
<style>
.gjnnl7s9m {
  d: path("M2.5 21.5H13l6.75-4.25a1.5 1.5 0 0 0-1.5-2.5l-1.75 1M7 3.5h8v5a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Zm8 1.75h1a2 2 0 0 1 0 4h-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxtnnnblw {
  d: path("M2.5 14.5h4.25l3 2H13a1 1 0 0 1 0 2H9.25");
}

</style>
