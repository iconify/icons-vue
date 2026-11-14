<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mz02n3byk"/><path class="o9bys4b8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-in-glove" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz02n3byk {
  d: path("m7.5 21.5l-1-4.5c-2.5-1.5-4-4.5-3-7C4.25 8.5 6 8.5 7 10l.5 1c-.5-5 2-8 6-8c4.5 0 7.5 3.5 7 8c-.5 4-2.5 6-3.5 6.5l-.5 4Z");
}

.o9bys4b8n {
  d: path("M10.25 10a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-3.5 8.5H17");
}

</style>
