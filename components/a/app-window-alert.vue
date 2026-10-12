<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="r-ub_ybqe"/><path class="h0757nbba"/><path class="vge_ec3ru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:app-window-alert" /></template>
<style>
.h0757nbba {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 6.5h.01m3.49 0h.01m3.49 0h.01");
}

.r-ub_ybqe {
  width: 18.5px;
  height: 17.5px;
  x: 2.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.vge_ec3ru {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.75h17");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
