<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ebtl3__4m"/><path class="mm2aryb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-bank" /></template>
<style>
.ebtl3__4m {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 5.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mm2aryb3d {
  d: path("M10 4.75v-1a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1m-6 6h8v2.5a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Zm4 6v2.5c0 1.25-.75 2-2 2H7.5");
}

</style>
