<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hi6u8r_is"/><path class="nef28zb6w"/><path class="p-0pfnval"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthing-pool" /></template>
<style>
.hi6u8r_is {
  d: path("M2.5 8.5a9.5 4.5 0 1 0 19 0a9.5 4.5 0 1 0-19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nef28zb6w {
  d: path("m2.5 8.5l1 8.5c.5 2.5 4 4.5 8.5 4.5s8-2 8.5-4.5l1-8.5");
}

.p-0pfnval {
  d: path("M6 8.5q2.25-1.5 4.5 0t4.5 0c1.5-1 2.5-.75 3.25-.25");
}

</style>
