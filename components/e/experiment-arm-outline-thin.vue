<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymw3aibdo"/><path class="rz466126m"/><path class="ew7bcuc4w"/><path class="on0qv5szw"/><path class="qmhkuacxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:experiment-arm-outline-thin" /></template>
<style>
.ew7bcuc4w {
  d: path("M13.5 6.5 18 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.on0qv5szw {
  d: path("M2 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qmhkuacxl {
  d: path("M17 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rz466126m {
  d: path("M10.5 6.5 6 11");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
