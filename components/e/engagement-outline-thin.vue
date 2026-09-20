<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrzizubal"/><path class="uu-axlbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:engagement-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrzizubal {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.uu-axlbah {
  d: path("m9 8 3 -3 3 3Z");
}

</style>
