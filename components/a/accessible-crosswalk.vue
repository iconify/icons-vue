<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="t0v21rbsq"/><rect class="qa_ab_9cp"/><rect class="dqt5sjtdl"/><path class="pxmn6eb9l"/><path class="q9pnr2wro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-crosswalk" /></template>
<style>
.dqt5sjtdl {
  width: 4px;
  height: 6.25px;
  x: 17.25px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.pxmn6eb9l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 3.5h.01");
}

.q9pnr2wro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6v3.25h3.25l1 2.5M9.15 7.6A2.75 2.75 0 1 0 13 11.75");
}

.qa_ab_9cp {
  width: 4px;
  height: 6.25px;
  x: 10px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.t0v21rbsq {
  width: 4px;
  height: 6.25px;
  x: 2.75px;
  y: 15px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
