<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pf564qbbm"/><path class="dlpa-frlb"/><path class="ez875nbbx"/><path class="n30k87bda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:degree-duotone-bold" /></template>
<style>
.dlpa-frlb {
  fill: currentColor;
  d: path("M5 16a2 2 0 0 0 0 4h14a2 2 0 0 0 0 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ez875nbbx {
  d: path("m2 8 4 -4h12l4 4 -4 4H6Z");
}

.n30k87bda {
  d: path("M5 16a2 2 0 0 0 0 4h14a2 2 0 0 0 0 -4Z");
}

.pf564qbbm {
  fill: currentColor;
  d: path("m2 8 4 -4h12l4 4 -4 4H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
