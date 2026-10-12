<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="l3tiebc2r"/><rect class="y92wecc3d"/><rect class="buyua78xt"/><rect class="zfb5tsl9d"/><path class="exj_d774i"/><path class="w-bktbcas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-swarm" /></template>
<style>
.buyua78xt {
  width: 6px;
  height: 6px;
  x: 2.75px;
  y: 15.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.exj_d774i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 5.75h.01m12.49 0h.01M5.75 18.25h.01m12.49 0h.01");
}

.l3tiebc2r {
  width: 6px;
  height: 6px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.w-bktbcas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

.y92wecc3d {
  width: 6px;
  height: 6px;
  x: 15.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zfb5tsl9d {
  width: 6px;
  height: 6px;
  x: 15.25px;
  y: 15.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

</style>
