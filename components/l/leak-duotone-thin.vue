<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jln5-9bda"/><path class="mqtixbwqo"/><path class="saqo5mbad"/><path class="mj3xlxbyp"/><path class="kgr7y94lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leak-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jln5-9bda {
  fill: currentColor;
  d: path("m12 13 2.5 2.5a3 3 0 1 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kgr7y94lw {
  d: path("m12 13 2.5 2.5a3 3 0 1 1 -5 0Z");
}

.mj3xlxbyp {
  d: path("M14 5v6");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.saqo5mbad {
  d: path("M10 5v6");
}

</style>
