<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wl-2sybgu"/><path class="x-3euebad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-licence" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wl-2sybgu {
  d: path("m3.726 6.719l.636-2A1.75 1.75 0 0 1 6.03 3.5h11.94a1.75 1.75 0 0 1 1.668 1.219l.636 2A1.75 1.75 0 0 1 18.607 9H5.393a1.75 1.75 0 0 1-1.667-2.281M4.5 9v11.5h8.8m6.2-7.1V9");
}

.x-3euebad {
  d: path("M7.5 20.5v-6H11v6m3.75-2.5l2 2L21 15.75");
}

</style>
