<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2mmeqs3c"/><path class="znukyabye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leg-cast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2mmeqs3c {
  d: path("M7 2.5v14c0 2.75 1.75 5 4.5 5H17v-5h-3.5v-14M7 5.5h6.5m5.75 11.75h.01m.49 2h.01m-.51 2h.01");
}

.znukyabye {
  d: path("M8.5 11c.75-1.5 1.75 1.5 2.5 0c.5-1 1 0 1.25-.5");
}

</style>
