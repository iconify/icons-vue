<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bxsijvklq"/><path class="zczxv-gqx"/><path class="xr8t5tbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-preview" /></template>
<style>
.bxsijvklq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

.xr8t5tbva {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.625 17.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zczxv-gqx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4M14 17.5c1.75-3.25 5.5-3.25 7.25 0c-1.75 3.25-5.5 3.25-7.25 0");
}

</style>
