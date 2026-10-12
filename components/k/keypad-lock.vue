<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lhr523bji"/><path class="fncz6gbqd"/><path class="q67jh0b2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keypad-lock" /></template>
<style>
.fncz6gbqd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 6.5h.01m3.49 0h.01M7.75 10h.01m3.49 0h.01m-3.51 3.5h.01m3.49 0h.01");
}

.lhr523bji {
  width: 9.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.q67jh0b2x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 17.25h7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
