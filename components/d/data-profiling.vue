<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuk2p4nmn"/><path class="f0a5_1dcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-profiling" /></template>
<style>
.cuk2p4nmn {
  d: path("M5.625 10.5h12.75A2.625 2.625 0 0 1 21 13.125v5.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-5.75A2.625 2.625 0 0 1 5.625 10.5m6.375 0v11m-9-7.25h18m-18 3.5h18");
}

.f0a5_1dcz {
  fill: currentColor;
  d: path("M13 8V5h1.75v3Zm3.25 0V2.5H18V8Zm3 0V6H21v2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
