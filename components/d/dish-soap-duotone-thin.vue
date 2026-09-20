<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ey1zq2xuk"/><path class="crm2eebhm"/><path class="ktolme9hl"/><path class="qdo_xac7v"/><path class="bo88vlbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dish-soap-duotone-thin" /></template>
<style>
.bo88vlbuz {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.crm2eebhm {
  fill: currentColor;
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ey1zq2xuk {
  fill: currentColor;
  d: path("M6 21v-9c0 -2 2 -3 2 -4V5h4v3c0 1 2 2 2 4v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktolme9hl {
  d: path("M6 21v-9c0 -2 2 -3 2 -4V5h4v3c0 1 2 2 2 4v9Z");
}

.qdo_xac7v {
  d: path("M8 5V2h4v3");
}

</style>
