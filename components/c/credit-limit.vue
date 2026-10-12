<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lo_lt5b5d"/><path class="cflc5ha_d"/><path class="vrxzsk89v"/><path class="qhx66-4er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:credit-limit" /></template>
<style>
.cflc5ha_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9h18.5M6.5 14.5H12");
}

.lo_lt5b5d {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.qhx66-4er {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 12.5v4");
}

.vrxzsk89v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 14.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
