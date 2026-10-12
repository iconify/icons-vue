<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="o02mj5bnb"/><path class="q7qjh0bue"/><path class="u_p9z_fnh"/><path class="m0zwk_bqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-card" /></template>
<style>
.m0zwk_bqg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.69 12.06a2.75 2.75 0 0 1 0 3.88m1.6-5.48a5 5 0 0 1 0 7.08");
}

.o02mj5bnb {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.q7qjh0bue {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 6.75h11.5");
}

.u_p9z_fnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 14h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
