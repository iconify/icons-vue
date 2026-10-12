<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dilf7rb5e"/><rect class="wjr0zib4x"/><path class="zfz3fzbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fax-machine" /></template>
<style>
.dilf7rb5e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 8.25a2.4 2.4 0 0 1 4.75 0M11 11V3.75h6.75V11");
}

.wjr0zib4x {
  width: 18.5px;
  height: 10.25px;
  x: 2.75px;
  y: 11px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zfz3fzbhl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16.25h.01m3.99 0h.01m3.99 0h.01");
}

</style>
