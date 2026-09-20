<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9oh1gxrx"/><path class="n32o5nlfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coins-outline-thin" /></template>
<style>
.d9oh1gxrx {
  d: path("M4 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n32o5nlfd {
  d: path("M10 11a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
