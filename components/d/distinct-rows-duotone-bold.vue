<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b2fhghbcn"/><path class="a_4nlgd6u"/><path class="grgincavq"/><path class="avcp11bgx"/><path class="iiq-sr0bx"/><path class="ytp_psb3u"/><path class="nvzooz8re"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distinct-rows-duotone-bold" /></template>
<style>
.a_4nlgd6u {
  fill: currentColor;
  d: path("M14 5.5A2.5 2.5 0 0 1 16.5 3h3A2.5 2.5 0 0 1 22 5.5 2.5 2.5 0 0 1 19.5 8h-3A2.5 2.5 0 0 1 14 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.avcp11bgx {
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h3A2.5 2.5 0 0 1 10 5.5 2.5 2.5 0 0 1 7.5 8h-3A2.5 2.5 0 0 1 2 5.5");
}

.b2fhghbcn {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h3A2.5 2.5 0 0 1 10 5.5 2.5 2.5 0 0 1 7.5 8h-3A2.5 2.5 0 0 1 2 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.grgincavq {
  fill: currentColor;
  d: path("M4 18.5A2.5 2.5 0 0 1 6.5 16h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iiq-sr0bx {
  d: path("M14 5.5A2.5 2.5 0 0 1 16.5 3h3A2.5 2.5 0 0 1 22 5.5 2.5 2.5 0 0 1 19.5 8h-3A2.5 2.5 0 0 1 14 5.5");
}

.nvzooz8re {
  d: path("M4 18.5A2.5 2.5 0 0 1 6.5 16h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ytp_psb3u {
  d: path("m6 8 6 6 6 -6");
}

</style>
