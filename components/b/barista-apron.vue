<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1nthabki"/><path class="h_02b9bat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barista-apron" /></template>
<style>
.b1nthabki {
  d: path("M8 7h8v3.5l3 1.5v8a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20v-8l3-1.5Zm0 0a4 4 0 0 1 8 0M5 12l-2.5 2.5M19 12l2.5 2.5");
}

.h_02b9bat {
  d: path("M10.75 15h2.5A1.75 1.75 0 0 1 15 16.75a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 16.75A1.75 1.75 0 0 1 10.75 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
