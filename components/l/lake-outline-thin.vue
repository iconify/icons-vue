<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nd-_isc6y"/><path class="rkhcgsbdl"/><path class="xn7bwccty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lake-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd-_isc6y {
  d: path("M4 12a8 5 0 1 0 16 0 8 5 0 1 0 -16 0");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.xn7bwccty {
  d: path("M8 6h8");
}

</style>
