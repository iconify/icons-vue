<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h99b60boa"/><path class="f5o58ynqs"/><path class="ihr2pemxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cross-dissolve" /></template>
<style>
.f5o58ynqs {
  d: path("M12.5 10H18a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 20h-5.5A3.5 3.5 0 0 1 9 16.5v-3a3.5 3.5 0 0 1 3.5-3.5");
}

.h99b60boa {
  d: path("M6 4h5.5A3.5 3.5 0 0 1 15 7.5v3a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihr2pemxb {
  fill: currentColor;
  d: path("M10.5 10h3a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 12.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
