<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vr3sgacxq"/><path class="qgqx27bzk"/><path class="d_xtg74gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:curry-outline-thin" /></template>
<style>
.d_xtg74gy {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgqx27bzk {
  d: path("M4 13a4 4 0 0 1 8 0");
}

.vr3sgacxq {
  d: path("M2 13h20c0 4 -4 7 -10 7S2 17 2 13");
}

</style>
