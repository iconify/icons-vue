<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="muc7gfbfp"/><rect class="eit0z3bev"/><path class="r9uljybpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:game-cartridge" /></template>
<style>
.eit0z3bev {
  width: 9px;
  height: 8px;
  x: 7.5px;
  y: 5.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.muc7gfbfp {
  d: path("M6.25 2.75h11.5Q19 2.75 19 4v13.75q0 1.25-.77 2.24l-.21.27q-.77.99-2.02.99H8q-1.25 0-2.02-.99l-.21-.27Q5 19 5 17.75V4q0-1.25 1.25-1.25");
}

.r9uljybpw {
  d: path("M8.75 16.75v2m2.5-2v2m2.5-2v2m2.5-2v1");
}

</style>
