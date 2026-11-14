<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dr10-2app"/><path class="rt4tjubwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-chief" /></template>
<style>
.dr10-2app {
  d: path("M4 18v-4.5a8 8 0 0 1 16 0V18M2.5 19.5L4 18h16l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rt4tjubwt {
  d: path("M9.25 8.75h5.5v2.75c0 1.75-1.25 2.75-2.75 3.5c-1.5-.75-2.75-1.75-2.75-3.5Z");
}

</style>
