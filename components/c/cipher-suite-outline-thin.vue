<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pae1rfb4b"/><path class="tturp2djn"/><path class="fkf_gcbra"/><path class="lqcp5xb1v"/><path class="a6m5p6bsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cipher-suite-outline-thin" /></template>
<style>
.a6m5p6bsi {
  d: path("M7 6.5h10");
}

.fkf_gcbra {
  d: path("M10 15h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqcp5xb1v {
  d: path("M4 3h16");
}

.pae1rfb4b {
  d: path("M7 13a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.tturp2djn {
  d: path("M9 11a3 3 0 0 1 6 0");
}

</style>
