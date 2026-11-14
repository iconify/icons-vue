<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tdpbj1ijk"/><path class="iy1vdac5b"/><path class="gp0g2x05u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-stone-massage" /></template>
<style>
.gp0g2x05u {
  d: path("M5 7.75a3.5 2.75 0 1 0 7 0a3.5 2.75 0 1 0-7 0M16.5 21.5q-1-1.5 0-3t0-3m2.5 6q-1-1.5 0-3t0-3m2.5 6q-1-1.5 0-3q.5-.75 0-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy1vdac5b {
  d: path("M3 13.25a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0");
}

.tdpbj1ijk {
  d: path("M2.5 18.75a5.5 2.75 0 1 0 11 0a5.5 2.75 0 1 0-11 0");
}

</style>
