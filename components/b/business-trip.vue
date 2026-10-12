<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w0_mt1r8h"/><path class="jpje4qd7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:business-trip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpje4qd7e {
  d: path("M7 11V9.75a1.5 1.5 0 0 1 1.5-1.5h1a1.5 1.5 0 0 1 1.5 1.5V11m-8.25 4.5h12.5m3-12.75v7m-3-2.75l3-1.5l3 1.5M17 9.75h2.5");
}

.w0_mt1r8h {
  width: 12.5px;
  height: 10.25px;
  x: 2.75px;
  y: 11px;
  rx: 2px;
}

</style>
