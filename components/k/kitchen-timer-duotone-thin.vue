<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tdwzb1a8u"/><path class="dr_svztcl"/><path class="g7fe9zb5k"/><path class="ays356bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kitchen-timer-duotone-thin" /></template>
<style>
.ays356bvr {
  d: path("m12 14 3 -3");
}

.dr_svztcl {
  d: path("M5.5 14a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

.g7fe9zb5k {
  d: path("M10 7.5V4h4v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdwzb1a8u {
  fill: currentColor;
  d: path("M5.5 14a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
