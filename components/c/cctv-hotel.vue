<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wydgmz-1n"/><path class="ncarcz5rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cctv-hotel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ncarcz5rt {
  d: path("M15.75 17v4.5h5V17");
}

.wydgmz-1n {
  d: path("M3 8v10m0-4h5.5V9.75m.385-6.394l7.282 2.65a2.625 2.625 0 0 1 1.569 3.365l-.256.705a2.625 2.625 0 0 1-3.365 1.568l-7.282-2.65a2.625 2.625 0 0 1-1.569-3.365l.256-.705a2.625 2.625 0 0 1 3.365-1.568M15.25 8.75h.01M14.75 18l3.5-3.25l3.5 3.25");
}

</style>
