<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="mn71pabsl"/><path class="fl0ti4b_o"/><path class="rd5kplbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bulldozer" /></template>
<style>
.fl0ti4b_o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 18.5h.01m3.74 0h.01m3.49 0h.01");
}

.mn71pabsl {
  width: 12.75px;
  height: 5.5px;
  x: 2.75px;
  y: 15.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.75px;
}

.rd5kplbyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.75v-8.5a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5v3.5H14a1 1 0 0 1 1 1v4Zm0 0h11.5m-9.5-6.5h1.5m8 4h3m0-2.5h1.5a1.5 1.5 0 0 1 1.5 1.5v7.5a1.5 1.5 0 0 1-1.5 1.5h-2.5C18 19.75 18.5 18 18.5 16s-.25-3.5-.25-5.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
