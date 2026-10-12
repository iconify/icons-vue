<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lw-xe2q0n"/><path class="t8zpppc2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gallery-building" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lw-xe2q0n {
  width: 18.5px;
  height: 14.75px;
  x: 2.75px;
  y: 6.5px;
  rx: 1.5px;
}

.t8zpppc2j {
  d: path("M2.75 3.5h18.5M7 10h10v7.5H7Zm0 7.5l3.25-3.25l2.25 2.25L14 15l3 2.5");
}

</style>
