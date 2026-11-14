<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwkp65gco"/><path class="jtjaukemg"/><path class="kj1pbpbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bathroom-layout" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtjaukemg {
  d: path("M7.75 6zA2.25 2.25 0 0 1 10 8.25v7.5A2.25 2.25 0 0 1 7.75 18a2.25 2.25 0 0 1-2.25-2.25v-7.5A2.25 2.25 0 0 1 7.75 6m7.75 0H17a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 17 9h-1.5A1.5 1.5 0 0 1 14 7.5A1.5 1.5 0 0 1 15.5 6");
}

.kj1pbpbgz {
  d: path("M14.25 12.25a2 3.25 0 1 0 4 0a2 3.25 0 1 0-4 0");
}

.pwkp65gco {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 6 3");
}

</style>
