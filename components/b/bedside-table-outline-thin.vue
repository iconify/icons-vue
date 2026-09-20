<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="codbx8bow"/><path class="y07a50u1t"/><path class="ffwaozrbk"/><path class="tbcegmb1y"/><path class="quvbquwsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bedside-table-outline-thin" /></template>
<style>
.codbx8bow {
  d: path("M5 18V7h14v11Z");
}

.ffwaozrbk {
  d: path("M10 10h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.quvbquwsr {
  d: path("M17 18v3");
}

.tbcegmb1y {
  d: path("M7 18v3");
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
