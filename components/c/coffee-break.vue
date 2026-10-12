<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bfxoxdbjh"/><path class="qhipurbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coffee-break" /></template>
<style>
.bfxoxdbjh {
  width: 12px;
  height: 11.5px;
  x: 3.75px;
  y: 9.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qhipurbtq {
  d: path("M15.75 11.75h1.5a2.5 2.5 0 0 1 0 5h-1.5M8.25 13v4.25m3-4.25v4.25m-3.5-14q-1 1.5 0 3m4-3q-1 1.5 0 3");
}

</style>
