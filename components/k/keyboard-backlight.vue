<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="o0xk3dbag"/><path class="ytqem2jgw"/><path class="bie4swl8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keyboard-backlight" /></template>
<style>
.bie4swl8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 14.25h7.5");
}

.o0xk3dbag {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytqem2jgw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 9.75h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

</style>
