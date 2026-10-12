<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jbmrxfbpj"/><path class="su7wuov-l"/><path class="qs7as0b1o"/><circle class="eav5g_b0l"/><circle class="y9y1r0c9o"/><rect class="kmdo48-uv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gimbal-stabilizer" /></template>
<style>
.eav5g_b0l {
  cx: 4.5px;
  cy: 5.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbmrxfbpj {
  width: 13.5px;
  height: 5px;
  x: 7.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.kmdo48-uv {
  width: 4px;
  height: 7.25px;
  x: 10px;
  y: 14px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.qs7as0b1o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 11.5H6A1.5 1.5 0 0 1 4.5 10V6.75M6 5.25h1.75");
}

.su7wuov-l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9y1r0c9o {
  cx: 12px;
  cy: 11.5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
