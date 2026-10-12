<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="z1kgyetnn"/><path class="stev3uadc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:disabled-parking" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.stev3uadc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7.25v4.25h3.75l1.75 3.75h1.25m-6.75-6h3m-5.25 1a3.5 3.5 0 1 0 5 4.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z1kgyetnn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5.25h.01");
}

</style>
