<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bz031_o7j"/><path class="vivg927sx"/><path class="p98lnpivc"/><path class="u7wu02-dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cradle-cap" /></template>
<style>
.bz031_o7j {
  d: path("M3 12.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p98lnpivc {
  fill: currentColor;
  d: path("m7.51 7.533l.259-.074A.68.68 0 0 1 8.625 8a.89.89 0 0 1-.596.99L8 9a.79.79 0 0 1-1-.5a.757.757 0 0 1 .51-.967m4.493-1.641l.244-.034a.78.78 0 0 1 .878.642a.743.743 0 0 1-.628.858l-.244.034a.78.78 0 0 1-.878-.642a.743.743 0 0 1 .628-.858m4 1.75l.255-.036A.65.65 0 0 1 17 8.25a.885.885 0 0 1-.74.873l-.01.002a.76.76 0 0 1-.875-.625a.743.743 0 0 1 .628-.858");
}

.u7wu02-dj {
  d: path("M7.75 13c.75.75 1.75.75 2.5 0m3.5 0c.75.75 1.75.75 2.5 0m-5.75 4q1.5 1.125 3 0");
}

.vivg927sx {
  d: path("M11.25 3.5c-.5-1.25 1.25-1.5 1.5-.5");
}

</style>
