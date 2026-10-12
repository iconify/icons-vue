<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="m9ax3qy2o"/><path class="x3yghbble"/><circle class="r-v9604fi"/><path class="ufcahkbfz"/><circle class="i316mtvax"/><path class="hz6nloawv"/><rect class="nz0c1bc1i"/><path class="km8pidclm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:field-trip" /></template>
<style>
.hz6nloawv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 19h.01");
}

.i316mtvax {
  cx: 12.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km8pidclm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 13.5V18");
}

.m9ax3qy2o {
  width: 12.5px;
  height: 9.5px;
  x: 2.75px;
  y: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.nz0c1bc1i {
  width: 3.5px;
  height: 9px;
  x: 17.75px;
  y: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.r-v9604fi {
  cx: 5.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ufcahkbfz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 19h.01");
}

.x3yghbble {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.25h12.5M9 7.25v4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
