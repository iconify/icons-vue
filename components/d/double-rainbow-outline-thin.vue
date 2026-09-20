<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydpucsi6v"/><path class="azjtlhb3x"/><path class="no90vc3pu"/><path class="wk7jmzmpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:double-rainbow-outline-thin" /></template>
<style>
.azjtlhb3x {
  d: path("M4 18a8 8 0 0 1 16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no90vc3pu {
  d: path("M7 18a5 5 0 0 1 10 0");
}

.wk7jmzmpf {
  d: path("M9 18a3 3 0 0 1 6 0");
}

.ydpucsi6v {
  d: path("M2 18a10 10 0 0 1 20 0");
}

</style>
