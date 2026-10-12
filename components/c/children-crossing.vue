<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="q6icwma0c"/><path class="bzped75xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:children-crossing" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.bzped75xf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 8.75l-.5 4l-2 4m2-4l2.5 1.5v3m-4.75-6.5l2.75-2l2.5 1.5m1.75 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.q6icwma0c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
