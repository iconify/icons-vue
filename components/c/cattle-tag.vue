<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hr5he0bxg"/><rect class="a9dg3srdv"/><path class="a5vfprbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cattle-tag" /></template>
<style>
.a5vfprbqd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10.5h.01m3.99 0h.01m-3.51 5.75h.01m2.99 0h.01");
}

.a9dg3srdv {
  width: 2.5px;
  height: 4.25px;
  x: 18.75px;
  y: 13px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.hr5he0bxg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5h5a2.5 2.5 0 0 1 2.5 2.5v7.25a5 5 0 0 1-10 0V7.5A2.5 2.5 0 0 1 8.25 5m-2.5 3.25h-2a.75.75 0 0 0-.6 1.2c.75 1 1.45 1.55 2.6 1.55Zm10 0h2.75a.75.75 0 0 1 .6 1.2c-.75 1-1.85 1.55-3.35 1.55Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
