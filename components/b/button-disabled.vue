<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_0d4cvxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:button-disabled" /></template>
<style>
.c_0d4cvxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19v8h-19Zm4.5 4h10m-3 10.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm1-2.5l5 5");
}

</style>
