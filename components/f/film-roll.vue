<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="gn05m-bht"/><rect class="n40cpk2ex"/><path class="c830hnbku"/><rect class="sxswfdcvm"/><path class="ugjldccos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-roll" /></template>
<style>
.c830hnbku {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h9m-9 9.75h9");
}

.gn05m-bht {
  width: 4px;
  height: 3.25px;
  x: 5.25px;
  y: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.n40cpk2ex {
  width: 9px;
  height: 14.75px;
  x: 2.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.sxswfdcvm {
  width: 9.5px;
  height: 8px;
  x: 11.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.ugjldccos {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 10.75h.01m3.49 0h.01m-3.51 4h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
