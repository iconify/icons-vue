<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3352wbon"/><path class="c0lx-yb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barn-doors" /></template>
<style>
.c0lx-yb_s {
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3352wbon {
  d: path("M9.625 7h4.75A2.625 2.625 0 0 1 17 9.625v4.75A2.625 2.625 0 0 1 14.375 17h-4.75A2.625 2.625 0 0 1 7 14.375v-4.75A2.625 2.625 0 0 1 9.625 7M7 7L3 4v16l4-3M17 7l4-3v16l-4-3");
}

</style>
