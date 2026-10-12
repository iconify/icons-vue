<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f0ob_2b3h"/><path class="djd7q6bbo"/><path class="yhlolccrq"/><rect class="plwp7ccab"/><path class="n-yf3vbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:https-lock" /></template>
<style>
.djd7q6bbo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8h18.5");
}

.f0ob_2b3h {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.n-yf3vbeo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 13.25v-.75a1.75 1.75 0 0 1 3.5 0v.75");
}

.plwp7ccab {
  width: 6.5px;
  height: 4.75px;
  x: 8.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yhlolccrq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5.9h.01m2.74 0h.01");
}

</style>
