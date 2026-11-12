<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="uac092bgj"/><path class="m99yuxjsm"/><path class="zsnush0dj"/><path class="wlfsgdzfw"/><path class="n04922jxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-minimalistic-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m99yuxjsm {
  d: path("M17 7L15 9");
}

.n04922jxw {
  d: path("M19 5L20 4");
}

.uac092bgj {
  cx: 9.5px;
  cy: 14.5px;
  r: 7.5px;
}

.wlfsgdzfw {
  d: path("M16 3.5L16.5 4.5");
}

.zsnush0dj {
  d: path("M19.5 7.5L20.5 8");
}

</style>
