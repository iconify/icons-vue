<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="v3x3kdbao"/><rect class="uv4pw9com"/><path class="r6w4a8bkh"/><path class="jm8-mwbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calculator-scientific" /></template>
<style>
.jm8-mwbsa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 15.75h.01m2.49 0h.01m2.49 0h.01m2.49 0h.01M8.25 18.5h.01m2.49 0h.01m2.49 0h.01m2.49 0h.01");
}

.r6w4a8bkh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 12.75h1m2.75 0h1m2.75 0h1");
}

.uv4pw9com {
  width: 8.5px;
  height: 4px;
  x: 7.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.v3x3kdbao {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
