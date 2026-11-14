<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dsvgj-blv"/><path class="fkr1nxb-x"/><path class="o8kd4oriz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ligament" /></template>
<style>
.dsvgj-blv {
  d: path("M9.5 2.5v4c-2.5.25-3 3.5-.5 3.75h6c2.5-.25 2-3.5-.5-3.75v-4m-5 19v-4c-2.5-.25-3-3.5-.5-3.75h6c2.5.25 2 3.5-.5 3.75v4");
}

.fkr1nxb-x {
  d: path("M15.155 7.495za1 1 0 0 1 .245 1.392l-5.162 7.373a1 1 0 0 1-1.393.245a1 1 0 0 1-.245-1.392l5.162-7.373a1 1 0 0 1 1.393-.245");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8kd4oriz {
  d: path("M8.845 7.495za1 1 0 0 1 1.393.245l5.162 7.373a1 1 0 0 1-.245 1.392a1 1 0 0 1-1.393-.245L8.6 8.887a1 1 0 0 1 .245-1.392");
}

</style>
