<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dcdwgqbou"/><circle class="lr1jhjbei"/><path class="gfbq9pbyh"/><circle class="bj2otrpqp"/><path class="zd9h-8b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:custody-family" /></template>
<style>
.bj2otrpqp {
  cx: 16px;
  cy: 14px;
  r: 1.6px;
}

.dcdwgqbou {
  d: path("M3.25 9.75L12 3.25l8.75 6.5");
}

.gfbq9pbyh {
  d: path("M4.5 18.75a3.5 3.5 0 0 1 7 0v1.5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr1jhjbei {
  cx: 8px;
  cy: 11.5px;
  r: 2px;
}

.zd9h-8b3d {
  d: path("M13.75 19.5a2.25 2.25 0 0 1 4.5 0v.75a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1Z");
}

</style>
