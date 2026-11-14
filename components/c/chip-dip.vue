<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nh-ptowow"/><path class="l0m81fb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chip-dip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0m81fb9x {
  d: path("M3 10a2 2 0 0 1 0 4M6.5 3v4M10 3v4m3.5-4v4M17 3v4M6.5 17v4m3.5-4v4m3.5-4v4m3.5-4v4");
}

.nh-ptowow {
  d: path("M5.625 7h12.75A2.625 2.625 0 0 1 21 9.625v4.75A2.625 2.625 0 0 1 18.375 17H5.625A2.625 2.625 0 0 1 3 14.375v-4.75A2.625 2.625 0 0 1 5.625 7");
}

</style>
