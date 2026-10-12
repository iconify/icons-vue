<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="icc1v1yqn"/><circle class="xttzr879b"/><circle class="fvsu8ubvu"/><circle class="p01uf6b6n"/><circle class="l6gcy4nyz"/><path class="ydc96fu9t"/><path class="e84hrrbda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-reel-sharp" /></template>
<style>
.e84hrrbda {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 19.25l2.25 2h8");
}

.fvsu8ubvu {
  cx: 15.25px;
  cy: 11px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icc1v1yqn {
  cx: 11px;
  cy: 11px;
  r: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6gcy4nyz {
  cx: 6.75px;
  cy: 11px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p01uf6b6n {
  cx: 11px;
  cy: 15.25px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xttzr879b {
  cx: 11px;
  cy: 6.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydc96fu9t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 11h.01");
}

</style>
