<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tv_y06bgj"/><path class="liucm7_ra"/><path class="uxl9_oo-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ensemble-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.liucm7_ra {
  d: path("m7 13 3 3 -3 3 -3 -3Z");
}

.tv_y06bgj {
  d: path("m12 3 3 3 -3 3 -3 -3Z");
}

.uxl9_oo-x {
  d: path("m17 13 3 3 -3 3 -3 -3Z");
}

</style>
