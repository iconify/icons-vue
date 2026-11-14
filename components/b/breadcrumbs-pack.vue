<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps89usblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breadcrumbs-pack" /></template>
<style>
.ps89usblc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 10l3-2l3 2l3-2l3 2v9.5a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2Zm4.742-7.309l.869.134A1.08 1.08 0 0 1 9 4.125a1.32 1.32 0 0 1-1.398 1.029l-.6-.05A1.236 1.236 0 0 1 5.875 3.75a1.19 1.19 0 0 1 1.367-1.059m7.639.096l.405-.062a1.5 1.5 0 0 1 1.708 1.236L17 4a1.39 1.39 0 0 1-1.266 1.617l-.385.029a1.5 1.5 0 0 1-1.591-1.227l-.008-.044a1.36 1.36 0 0 1 1.131-1.588m4.37 6.482l.266-.041a1.5 1.5 0 0 1 1.711 1.255l.026.167a1.5 1.5 0 0 1-1.368 1.724l-.267.021a1.5 1.5 0 0 1-1.595-1.249L18 10.998a1.5 1.5 0 0 1 1.251-1.729");
}

</style>
