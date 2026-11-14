<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydzdxmkbd"/><path class="pf8ez5bvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consolidated-statements" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pf8ez5bvy {
  d: path("M8 6V5a2.5 2.5 0 0 1 2.5-2.5h7A2.5 2.5 0 0 1 20 5v10.5a2.5 2.5 0 0 1-2.5 2.5h-1m-9 0v-3m3 3v-5.5m3 5.5V9.5");
}

.ydzdxmkbd {
  d: path("M8 6h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V9.5A3.5 3.5 0 0 1 8 6");
}

</style>
