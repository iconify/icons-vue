<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-v3knb-a"/><path class="qbq59yb6c"/><path class="bac4tq45c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:business-trip-outline-thin" /></template>
<style>
.a-v3knb-a {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.bac4tq45c {
  d: path("m11 2 2.5 2.5H19L16.5 7H11Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qbq59yb6c {
  d: path("M9 12V9.5h6V12");
}

</style>
