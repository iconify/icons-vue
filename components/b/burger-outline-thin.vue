<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h0mp_outl"/><path class="z8g2jgblp"/><path class="yvj012pxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:burger-outline-thin" /></template>
<style>
.h0mp_outl {
  d: path("M5 9c0 -4 3 -7 7 -7s7 3 7 7Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvj012pxv {
  d: path("M5 15h14v3a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3Z");
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
