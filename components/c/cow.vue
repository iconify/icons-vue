<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="u85jxf69b"/><rect class="z-00eym_b"/><path class="qpnu2ixfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cow" /></template>
<style>
.qpnu2ixfr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 17.5h.01m4.99 0h.01M9.5 10.25h.01m4.99 0h.01");
}

.u85jxf69b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 14.7V8.75a2.5 2.5 0 0 1 2.5-2.5h7a2.5 2.5 0 0 1 2.5 2.5v5.95M6 9.25H3.75a.75.75 0 0 0-.65 1.1C3.7 11.45 4.75 12 6 12Zm12 0h2.25a.75.75 0 0 1 .65 1.1C20.3 11.45 19.25 12 18 12Zm-9.75-3c-2-.5-3.25-1.75-3.5-3.5m11 3.5c2-.5 3.25-1.75 3.5-3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z-00eym_b {
  width: 14px;
  height: 7.75px;
  x: 5px;
  y: 13.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.75px;
}

</style>
