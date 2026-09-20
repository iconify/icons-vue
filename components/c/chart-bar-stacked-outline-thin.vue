<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r7dke9bth"/><path class="w8gxvdb9g"/><path class="c2hjexb6t"/><path class="nne1mobhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-stacked-outline-thin" /></template>
<style>
.c2hjexb6t {
  d: path("M4 14h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nne1mobhl {
  d: path("M12 14h5");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.r7dke9bth {
  d: path("M4 8h7");
}

.w8gxvdb9g {
  d: path("M14 8h5");
}

</style>
