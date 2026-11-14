<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dll46s03a"/><path class="x39l2gb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clipboard-paste" /></template>
<style>
.dll46s03a {
  d: path("M8 21H6.5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x39l2gb6y {
  d: path("M13.625 10h3.75A2.625 2.625 0 0 1 20 12.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 11 18.875v-6.25A2.625 2.625 0 0 1 13.625 10M10.75 3h2.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-2.5A2.25 2.25 0 0 1 8.5 5.25A2.25 2.25 0 0 1 10.75 3M14 14h3m-3 3.5h3");
}

</style>
