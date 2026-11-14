<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhm3ies2w"/><path class="yrpah0byk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hairpin-turn" /></template>
<style>
.hhm3ies2w {
  d: path("M2.5 21.5v-13a6.5 6.5 0 0 1 13 0V13c0 2.5 1.5 3.5 6 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrpah0byk {
  d: path("M6 21.5v-13a3 3 0 0 1 6 0V14c0 4.5 3 6 9.5 6");
}

</style>
