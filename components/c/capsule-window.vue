<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="c_86oibfw"/><path class="q7uogjb6l"/><path class="bfi22y6kp"/><path class="tyba--flk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:capsule-window" /></template>
<style>
.bfi22y6kp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 15.75a10 10 0 0 1 7.5-3.5v2.5a1 1 0 0 1-1 1Z");
}

.c_86oibfw {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 5px;
}

.q7uogjb6l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6h6a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3");
}

.tyba--flk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 9.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
