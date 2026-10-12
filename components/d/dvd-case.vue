<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jf60lda-p"/><path class="k6oyf8z7i"/><circle class="vu-e9cbtj"/><path class="xvzerlwtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dvd-case" /></template>
<style>
.jf60lda-p {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.k6oyf8z7i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75v18.5");
}

.vu-e9cbtj {
  cx: 13.75px;
  cy: 12px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xvzerlwtb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
