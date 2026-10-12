<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gy45x3b2i"/><rect class="rn_971b6b"/><path class="b5o-vl44n"/><circle class="e7r6i8bmq"/><path class="d-a013hlq"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:luggage-cart" /></template>
<style>
.b5o-vl44n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 7.75v-2A.75.75 0 0 1 13.5 5h2a.75.75 0 0 1 .75.75v2");
}

.d-a013hlq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 19h.01");
}

.e7r6i8bmq {
  cx: 9.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gy45x3b2i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h1.5a1 1 0 0 1 1 .85L7 16.75h13.5");
}

.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.rn_971b6b {
  width: 10.5px;
  height: 6px;
  x: 9.25px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
