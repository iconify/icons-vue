<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="rbmh0nbrd"/><rect class="zh67dybdq"/><rect class="ab1vxsb6u"/><path class="vjc137vuw"/><circle class="o4t0kqbkr"/><path class="qir7ovodz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-target" /></template>
<style>
.ab1vxsb6u {
  width: 3.5px;
  height: 6px;
  x: 16.75px;
  y: 14.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.o4t0kqbkr {
  cx: 19.25px;
  cy: 8.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qir7ovodz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.25 8.75h.01");
}

.rbmh0nbrd {
  width: 3.5px;
  height: 7.5px;
  x: 3.75px;
  y: 12.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.vjc137vuw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75H16.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zh67dybdq {
  width: 3.5px;
  height: 14.5px;
  x: 10.25px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
