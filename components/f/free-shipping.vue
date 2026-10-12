<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="nnmvv6b6i"/><path class="o2s481b3i"/><path class="m9f7spw1x"/><circle class="a9bxk79um"/><circle class="jn0v4eh1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:free-shipping" /></template>
<style>
.a9bxk79um {
  cx: 7px;
  cy: 19px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jn0v4eh1r {
  cx: 17.5px;
  cy: 19px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9f7spw1x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 10.75h.01");
}

.nnmvv6b6i {
  width: 8.75px;
  height: 7.5px;
  x: 2.75px;
  y: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.o2s481b3i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 7.5h4l1.75 2.5v3a1 1 0 0 1-1 1H15.5a1 1 0 0 1-1-1V8.5a1 1 0 0 1 1-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
