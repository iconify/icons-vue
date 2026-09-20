<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j979p1bmx"/><path class="pyliisb1b"/><path class="l0v-b4kbr"/><path class="hm--inbem"/><path class="bu6goduan"/><path class="swt86hbgr"/><path class="gcn2u0bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotel-gym-duotone-thin" /></template>
<style>
.bu6goduan {
  d: path("M16 7v10h3V7Z");
}

.gcn2u0bqi {
  d: path("M21.5 10v4");
}

.hm--inbem {
  d: path("M5 7v10h3V7Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j979p1bmx {
  fill: currentColor;
  d: path("M5 7v10h3V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.pyliisb1b {
  fill: currentColor;
  d: path("M16 7v10h3V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.swt86hbgr {
  d: path("M2.5 10v4");
}

</style>
