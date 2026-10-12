<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uovtt2bny"/><path class="gkbdaabsq"/><path class="i5lu8dbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blueprint-roll" /></template>
<style>
.gkbdaabsq {
  d: path("M5.25 4.75v5m-.25 0h14v9.5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5lu8dbkg {
  d: path("M8 13h4v5m0-2.5h4");
}

.uovtt2bny {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
