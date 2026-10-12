<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="wfdnybbtq"/><rect class="fnny04boh"/><path class="d0lzb8bkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grimace" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d0lzb8bkb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.33 13.5v4m3.34-4v4");
}

.fnny04boh {
  width: 10px;
  height: 4px;
  x: 7px;
  y: 13.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.wfdnybbtq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10h.01M15 10h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
