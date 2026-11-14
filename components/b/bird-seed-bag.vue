<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iy65mbbuy"/><path class="uvs60x3gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bird-seed-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy65mbbuy {
  d: path("m5.5 9l-2 10.5A1.5 1.5 0 0 0 5 21h12a1.5 1.5 0 0 0 1.5-1.5L16.5 9ZM8 9q1-3.25 5.75-2.75a2.5 2.5 0 1 1 3.5 1.5L16.5 9");
}

.uvs60x3gv {
  d: path("m18.25 4.25l2.5 1.25l-2.5 1.25M5 12.5h12");
}

</style>
