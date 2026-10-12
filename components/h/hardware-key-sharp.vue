<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w6bc2rqej"/><path class="ed-xnxz9s"/><circle class="ctk1fcczq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hardware-key-sharp" /></template>
<style>
.ctk1fcczq {
  cx: 12px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ed-xnxz9s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w6bc2rqej {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5H17.5v9H2.75zm14.75 2h3.75v5H17.5z");
}

</style>
