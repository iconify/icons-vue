<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="tibu_bctd"/><circle class="pprsu-mfw"/><path class="etlx6tb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:archery" /></template>
<style>
.etlx6tb6k {
  d: path("m11 13l8.25-8.25m-2.5-.5v3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pprsu-mfw {
  cx: 11px;
  cy: 13px;
  r: 4.25px;
}

.tibu_bctd {
  cx: 11px;
  cy: 13px;
  r: 8.25px;
}

</style>
