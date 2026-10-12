<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nl2k1rbzy"/><rect class="m1ssw_wgd"/><path class="axicz9bjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hybrid-work" /></template>
<style>
.axicz9bjw {
  d: path("M16.5 8h2.25m-2.25 4h2.25m-2.25 4h2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1ssw_wgd {
  width: 7.25px;
  height: 17.5px;
  x: 14px;
  y: 3.75px;
  rx: 1.5px;
}

.nl2k1rbzy {
  d: path("m2.75 12.75l4-3.5l4 3.5v6.5a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2Zm4 8.5v-3");
}

</style>
