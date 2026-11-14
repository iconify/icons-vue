<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxl_fab9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:head-lice-comb" /></template>
<style>
.lxl_fab9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19v4h-19Zm1.5 4v8m3-8v8m3-8v8m3-8v5.2m0 .4v2.4m3-8v3.9m3-3.9V11m-3.5 7.75a2.5 2.75 0 1 0 5 0a2.5 2.75 0 1 0-5 0ZM18 16v5.5m-1.5-7.25l.75 1.75m2.25-1.75L18.75 16m-4.5 2.75h1.25m5 0h1.25");
}

</style>
