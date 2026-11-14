<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cag61wbgr"/><path class="lstob1boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:downtime" /></template>
<style>
.cag61wbgr {
  d: path("m16.61 11.436l.271.193a1.39 1.39 0 0 1 .494 1.621a1.23 1.23 0 0 1-1.418.768l-.517-.115a1.29 1.29 0 0 0-1.19.347a1.29 1.29 0 0 0-.347 1.19l.115.517a1.23 1.23 0 0 1-.768 1.418a1.39 1.39 0 0 1-1.621-.494l-.193-.271A1.46 1.46 0 0 0 10.25 16a1.46 1.46 0 0 0-1.186.61l-.193.271a1.39 1.39 0 0 1-1.621.494a1.23 1.23 0 0 1-.768-1.418l.115-.517a1.29 1.29 0 0 0-.347-1.19a1.29 1.29 0 0 0-1.19-.347l-.517.115a1.23 1.23 0 0 1-1.418-.768a1.39 1.39 0 0 1 .494-1.621l.271-.193a1.46 1.46 0 0 0 .61-1.186a1.46 1.46 0 0 0-.61-1.186l-.271-.193a1.39 1.39 0 0 1-.494-1.621a1.23 1.23 0 0 1 1.418-.768l.517.115a1.29 1.29 0 0 0 1.19-.347a1.29 1.29 0 0 0 .347-1.19l-.115-.517a1.23 1.23 0 0 1 .768-1.418a1.39 1.39 0 0 1 1.621.494l.193.271a1.46 1.46 0 0 0 1.186.61a1.46 1.46 0 0 0 1.186-.61l.193-.271a1.39 1.39 0 0 1 1.621-.494a1.23 1.23 0 0 1 .768 1.418l-.115.517a1.29 1.29 0 0 0 .347 1.19a1.29 1.29 0 0 0 1.19.347l.517-.115a1.23 1.23 0 0 1 1.418.768a1.39 1.39 0 0 1-.494 1.621l-.271.193A1.46 1.46 0 0 0 16 10.25a1.46 1.46 0 0 0 .61 1.186");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lstob1boq {
  d: path("M7.75 10.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m10 6.25v5.25m3.5-5.25v5.25");
}

</style>
