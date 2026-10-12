<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="d6klj_saq"/><path class="srwloktrn"/><path class="erg1mi22d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crossword" /></template>
<style>
.d6klj_saq {
  width: 18px;
  height: 18px;
  x: 3px;
  y: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.erg1mi22d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4h4v4h-4Zm1 2h2M4 16h4v4H4Zm1 2h2");
}

.srwloktrn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3v18m6-18v18M3 9h18M3 15h18");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
