<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="a1o4xubwn"/><path class="cccb48rhk"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="r6parkbau"/><path class="t66ctv5hf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container-truck" /></template>
<style>
.a1o4xubwn {
  width: 11.25px;
  height: 10.25px;
  x: 2.75px;
  y: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.cccb48rhk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9v5m3-5v5m3-5v5m5-4.25a1 1 0 0 1 1-1h.9a1.5 1.5 0 0 1 1.25.67l1.1 1.6c.17.25.25.55.25.85v4.88h-4.5Zm0 2.5h4.5");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6parkbau {
  cx: 19px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t66ctv5hf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 19h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
