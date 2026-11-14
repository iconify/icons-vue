<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo-wxdh9d"/><path class="ceuvu2t_y"/><path class="ni9_rqbre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:actress" /></template>
<style>
.ceuvu2t_y {
  d: path("m12 5.5l-4.5-3V5Zm0 0l4.5-3V5Zm-3 7.25a1.75 1.75 0 0 1 0-3.5m6 3.5a1.75 1.75 0 0 1 0-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni9_rqbre {
  d: path("M13.539 9.271a4.5 4.5 0 0 1 0 8.458");
}

.qo-wxdh9d {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

</style>
