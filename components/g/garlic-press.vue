<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xga4-ubjl"/><path class="axlbu-bbs"/><rect class="idyi61mry"/><path class="hg-wfqbbx"/><path class="rlama4bbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garlic-press" /></template>
<style>
.axlbu-bbs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 7.5h.01");
}

.hg-wfqbbx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12.25h.01m2.99 0h.01");
}

.idyi61mry {
  width: 9px;
  height: 6px;
  x: 6px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.rlama4bbp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 17.75v2.75m2.5-2.75v2.75m2.5-2.75v2.75");
}

.xga4-ubjl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.25 7.5l17.5-4.25M3.25 7.5L5 9.25h15.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
