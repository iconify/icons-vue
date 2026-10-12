<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ij0r20jhq"/><circle class="d1b8m3wrq"/><circle class="oi17iu33t"/><path class="sihza2bkz"/><path class="hy-l-8bjo"/><circle class="yncg-kfwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cluster-dots" /></template>
<style>
.d1b8m3wrq {
  cx: 9px;
  cy: 4.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hy-l-8bjo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 13.6h.01m-1.66 2.85h.01m3.29 0h.01");
}

.ij0r20jhq {
  cx: 5.25px;
  cy: 7.5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oi17iu33t {
  cx: 8.75px;
  cy: 9.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sihza2bkz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 10.75a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 1 1 0-9.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yncg-kfwc {
  cx: 5.5px;
  cy: 17px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
