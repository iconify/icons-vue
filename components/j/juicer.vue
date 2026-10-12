<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dxp869bzl"/><path class="fzurz8blh"/><path class="pj2nckb9w"/><path class="d6wiphb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:juicer" /></template>
<style>
.d6wiphb3m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.25h5.25V11m-1.75 3h3.75q.75 0 .7.75l-.4 5.75q-.05.75-.8.75h-2.75q-.75 0-.8-.75l-.4-5.75q-.05-.75.7-.75");
}

.dxp869bzl {
  width: 10px;
  height: 18.5px;
  x: 3.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.fzurz8blh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5");
}

.pj2nckb9w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 16.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
