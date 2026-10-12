<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="i476d3bmh"/><path class="ysz39t4ug"/><rect class="zu1dm5b6s"/><path class="r4bz6u5cd"/><path class="d_tf1xr4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cash-register" /></template>
<style>
.d_tf1xr4o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.5h.01m2.49 0h.01m2.49 0h.01");
}

.i476d3bmh {
  width: 8px;
  height: 2.25px;
  x: 8px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.r4bz6u5cd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15h18m-11 2.6h4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysz39t4ug {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5v3M7 8h10q1 0 1.27.96l1.46 5.08Q20 15 19 15H5q-1 0-.73-.96l1.46-5.08Q6 8 7 8");
}

.zu1dm5b6s {
  width: 18px;
  height: 5.25px;
  x: 3px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
