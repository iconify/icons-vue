<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="m0-y0pcpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:die-cutter" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.m0-y0pcpn {
  d: path("m12 6.5l1.5 3.5l3.75.25l-3 2.5l1 3.75l-3.25-2l-3.25 2l1-3.75l-3-2.5L10.5 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
