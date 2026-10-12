<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wl44g0yyv"/><rect class="wd5iwrkxa"/><path class="ej1e9f33a"/><path class="u1k-zbcxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accordion" /></template>
<style>
.ej1e9f33a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 7.25l2.13-1.5L12 7.25l2.13-1.5l2.12 1.5v9.5l-2.12 1.5l-2.13-1.5l-2.12 1.5l-2.13-1.5Z");
}

.u1k-zbcxv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 9v.01m0 2.99v.01m0 2.99v.01");
}

.wd5iwrkxa {
  width: 5px;
  height: 12.5px;
  x: 16.25px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.wl44g0yyv {
  width: 5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
