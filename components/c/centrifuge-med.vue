<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="q51faobpf"/><path class="m-qkwu-jp"/><path class="ofu2-v9yz"/><path class="nk6m3ubza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:centrifuge-med" /></template>
<style>
.m-qkwu-jp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 16.75h4");
}

.nk6m3ubza {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.06 11.32l.88-1.89q.31-.68 1.06-.68h6q.75 0 1.06.68l.88 1.89q.31.68-.44.68h-9q-.75 0-.44-.68M7.5 6a5 2.5 0 0 1 9 0m0 0l.25-2m-.25 2l-2 .25");
}

.ofu2-v9yz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 16.75h.01");
}

.q51faobpf {
  width: 18.5px;
  height: 9.25px;
  x: 2.75px;
  y: 12px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
