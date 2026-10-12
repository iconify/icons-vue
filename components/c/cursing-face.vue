<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="zl9rnobhv"/><path class="dd_6j-l0z"/><path class="svf6rhblm"/><path class="q__3su1mk"/><path class="fh2d73b6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursing-face" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dd_6j-l0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

.fh2d73b6z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 14v3.5M15 15l2.5 1.5m-2.5 0l2.5-1.5");
}

.q__3su1mk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 17.5h.01");
}

.svf6rhblm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 13.5V18m2.25-4.5V18M6.5 14.5h4.25M6.5 17h4.25M13 13.75v1.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zl9rnobhv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 7.5L10 8.75m6.75-1.25L14 8.75");
}

</style>
