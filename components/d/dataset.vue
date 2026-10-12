<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><path class="jze4d7bam"/><path class="s1s_17bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dataset" /></template>
<style>
.hufrlzpcu {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.jze4d7bam {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7.5h7.5M10 12h7.5M10 16.5h7.5");
}

.s1s_17bkz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7.5h.01M6.75 12h.01m-.01 4.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
