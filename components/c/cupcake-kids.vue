<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud8e23bmd"/><path class="e8exvvdkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cupcake-kids" /></template>
<style>
.e8exvvdkb {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ud8e23bmd {
  d: path("M5 13h14l-1.5 8.5h-11Zm0 0c-1.5 0-1.5-3 1-3c0-2.5 3-3.5 6-3.5s6 1 6 3.5c2.5 0 2.5 3 1 3");
}

</style>
