<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pnk5ubc6h"/><circle class="eiufiabtg"/><circle class="h8r22mm8a"/><path class="u9es33d0u"/><rect class="v-22_jiug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brush-set" /></template>
<style>
.eiufiabtg {
  cx: 6px;
  cy: 6.75px;
  r: 1.75px;
}

.h8r22mm8a {
  cx: 18px;
  cy: 6.75px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnk5ubc6h {
  d: path("M12 2.75c1.25 1.4 1.9 2.4 1.9 3.25a1.9 1.9 0 0 1-3.8 0c0-.85.65-1.85 1.9-3.25");
}

.u9es33d0u {
  d: path("M12 8.65V12M7.2 8.3L9.5 12m7.3-3.7L14.5 12");
}

.v-22_jiug {
  width: 11.5px;
  height: 8.5px;
  x: 6.25px;
  y: 12.75px;
  rx: 2px;
}

</style>
