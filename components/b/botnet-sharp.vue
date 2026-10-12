<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="gzjsw6b-u"/><circle class="jqk4dobky"/><circle class="btr8vcg_o"/><circle class="tt0dxfbjt"/><path class="s_7cn8bzw"/><path class="auvnjbb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:botnet-sharp" /></template>
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

.s_7cn8bzw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 6.25L8.5 9m9.25-2.75L15.5 9m-9.25 8.75L8.5 15m9.25 2.75L15.5 15m-7-6h7v6h-7z");
}

.tt0dxfbjt {
  cx: 19.25px;
  cy: 19.25px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
