<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="gzjsw6b-u"/><circle class="jqk4dobky"/><circle class="btr8vcg_o"/><circle class="tt0dxfbjt"/><path class="s30y1ebjw"/><rect class="cr5lsgb5p"/><path class="auvnjbb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:botnet" /></template>
<style>
.auvnjbb-u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 12h.01m2.49 0h.01");
}

.btr8vcg_o {
  cx: 4.75px;
  cy: 19.25px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.cr5lsgb5p {
  width: 7px;
  height: 6px;
  x: 8.5px;
  y: 9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.gzjsw6b-u {
  cx: 4.75px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqk4dobky {
  cx: 19.25px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s30y1ebjw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 6.25L8.5 9m9.25-2.75L15.5 9m-9.25 8.75L8.5 15m9.25 2.75L15.5 15");
}

.tt0dxfbjt {
  cx: 19.25px;
  cy: 19.25px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
