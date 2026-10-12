<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jhxbx-m7t"/><path class="h0i21ubfa"/><circle class="e7r6i8bmq"/><path class="d-a013hlq"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:luggage-cart-sharp" /></template>
<style>
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

.h0i21ubfa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 7.75h10.5v6H9.25zm3.5 0V5h3.5v2.75");
}

.jhxbx-m7t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h1.5l.87-.01l.13.86L7 16.75h13.5");
}

.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
