<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvx_swewy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:align-right" /></template>
<style>
.vvx_swewy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h8.25A2.625 2.625 0 0 1 18 7.125v.25A2.625 2.625 0 0 1 15.375 10h-8.25A2.625 2.625 0 0 1 4.5 7.375v-.25A2.625 2.625 0 0 1 7.125 4.5m5 9.5h3.25A2.625 2.625 0 0 1 18 16.625v.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 9.5 16.875v-.25A2.625 2.625 0 0 1 12.125 14M21 2.5v19");
}

</style>
