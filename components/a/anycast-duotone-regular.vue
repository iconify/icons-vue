<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="jt2tjn0yv"/><path class="j_6juactj"/><path class="en2cmoxsx"/><path class="jmnql2iwe"/><path class="bo51iypxr"/><path class="f2d5k3gqj"/><path class="td_b5ht4u"/><path class="sc0mg_b_q"/><path class="vll23whqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anycast-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.en2cmoxsx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.11 14.22a6.5 6.5 0 0 1 -12.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f2d5k3gqj {
  d: path("M5.89 9.78a6.5 6.5 0 0 1 12.22 0");
}

.j_6juactj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2.6 8.58a10 10 0 0 1 18.8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jmnql2iwe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21.4 15.42a10 10 0 0 1 -18.8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt2tjn0yv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.89 9.78a6.5 6.5 0 0 1 12.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sc0mg_b_q {
  d: path("M18.11 14.22a6.5 6.5 0 0 1 -12.22 0");
}

.td_b5ht4u {
  d: path("M2.6 8.58a10 10 0 0 1 18.8 0");
}

.vll23whqv {
  d: path("M21.4 15.42a10 10 0 0 1 -18.8 0");
}

</style>
