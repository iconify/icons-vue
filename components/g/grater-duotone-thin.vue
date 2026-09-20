<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qvgbltbgf"/><path class="k_jhlzb9b"/><path class="ac5nw33zc"/><path class="a0tye7bdm"/><path class="yrhul2brc"/><path class="b4880zbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grater-duotone-thin" /></template>
<style>
.a0tye7bdm {
  d: path("M9 10h3");
}

.ac5nw33zc {
  d: path("M9 6a3 3 0 0 1 6 0");
}

.b4880zbbv {
  d: path("M9 18h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_jhlzb9b {
  d: path("M8 6h8c1 5 2 10 2 15H6c0 -5 1 -10 2 -15");
}

.qvgbltbgf {
  fill: currentColor;
  d: path("M8 6h8c1 5 2 10 2 15H6c0 -5 1 -10 2 -15");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yrhul2brc {
  d: path("M12 14h3");
}

</style>
