<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="rjannr7ij"/><path class="zp4s8wb4p"/><path class="bjzryejvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:license-plate" /></template>
<style>
.bjzryejvl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.75h4.25m3 0h4.25");
}

.rjannr7ij {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zp4s8wb4p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 9.25h.01m11.49 0h.01");
}

</style>
