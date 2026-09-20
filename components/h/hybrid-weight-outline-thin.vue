<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjze8rg7o"/><path class="k-qzacblk"/><path class="m5kk8acjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hybrid-weight-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-qzacblk {
  d: path("M7.5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.m5kk8acjv {
  d: path("M14 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mjze8rg7o {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

</style>
