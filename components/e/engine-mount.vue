<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mymru-_9y"/><rect class="m5k3dqb1a"/><path class="nt5zdi32f"/><rect class="imn24cbob"/><path class="ram43yxyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:engine-mount" /></template>
<style>
.imn24cbob {
  width: 18.5px;
  height: 4.25px;
  x: 2.75px;
  y: 17px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.m5k3dqb1a {
  width: 10px;
  height: 8px;
  x: 7px;
  y: 9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.mymru-_9y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V9m-1-4l2-1m-2 3.25l2-1");
}

.nt5zdi32f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 11.25c.75 1 .75 2.5 0 3.5m5.5-3.5c-.75 1-.75 2.5 0 3.5");
}

.ram43yxyd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 19.1h.01m12.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
