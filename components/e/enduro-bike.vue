<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nteeebc3v"/><path class="mw27kbbzb"/><path class="e23gtfbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:enduro-bike" /></template>
<style>
.e23gtfbbx {
  d: path("m3.5 8l6 1h6.75l-2.75 3H9Zm12.75 1.5l5.25-1");
}

.mw27kbbzb {
  d: path("m6 15l3-3m9 3l-2.5-8.5h-2");
}

.nteeebc3v {
  d: path("M2.5 15a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm12 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
