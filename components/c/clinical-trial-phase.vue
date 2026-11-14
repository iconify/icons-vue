<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eijuybbnf"/><path class="gb826cbxw"/><path class="a5uqb5btg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clinical-trial-phase" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.eijuybbnf {
  d: path("M3 18v-4h6v-4h6v8Z");
}

.gb826cbxw {
  fill: currentColor;
  d: path("M16.5 6h3A1.5 1.5 0 0 1 21 7.5v9a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-9A1.5 1.5 0 0 1 16.5 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
