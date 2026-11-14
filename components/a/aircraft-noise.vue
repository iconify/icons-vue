<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fy80jlbsl"/><path class="qyunu2nmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-noise" /></template>
<style>
.fy80jlbsl {
  d: path("M3 10h2l3 4h9.5c2.5 0 4 1.25 4 2.5S20 19 17.5 19h-12Zm10.5 9L11 21.5M12 10a3 3 0 0 1 4 1m-5.5-3.5a5.75 5.75 0 0 1 8 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyunu2nmv {
  d: path("M9.25 5.25a8.5 8.5 0 0 1 11.5 3");
}

</style>
