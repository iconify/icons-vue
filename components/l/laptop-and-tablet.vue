<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ckflqdk6f"/><rect class="q4til6mxl"/><path class="hfwhd-zqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-and-tablet" /></template>
<style>
.ckflqdk6f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3.75h12q2 0 2 1.75t-2 1.75h-5q-2 0-2 2v3.5q0 2-2 2h-3q-2 0-2-2v-7q0-2 2-2m-3 14.5h7.75");
}

.hfwhd-zqz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 18.5h.01");
}

.q4til6mxl {
  width: 7.5px;
  height: 11px;
  x: 13.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
