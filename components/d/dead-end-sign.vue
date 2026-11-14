<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7a-593kf"/><path class="eiw1ulbnj"/><path class="x2vewobfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dead-end-sign" /></template>
<style>
.eiw1ulbnj {
  fill: currentColor;
  d: path("M8.25 4.5h7.5A1.25 1.25 0 0 1 17 5.75A1.25 1.25 0 0 1 15.75 7h-7.5A1.25 1.25 0 0 1 7 5.75A1.25 1.25 0 0 1 8.25 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7a-593kf {
  d: path("M6.375 2h11.25A4.375 4.375 0 0 1 22 6.375v6.25A4.375 4.375 0 0 1 17.625 17H6.375A4.375 4.375 0 0 1 2 12.625v-6.25A4.375 4.375 0 0 1 6.375 2M12 17v5");
}

.x2vewobfi {
  d: path("M12 7v7.5");
}

</style>
