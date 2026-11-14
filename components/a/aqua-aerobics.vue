<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olxh4hbjn"/><path class="psw2nycot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aqua-aerobics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olxh4hbjn {
  d: path("M9.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.psw2nycot {
  d: path("m4.25 4.5l2.75 8c.75-1.25 2.5-2 5-2s4.25.75 5 2l2.75-8M7 12.5V17m10-4.5V17M2.5 17q2.25-1.5 4.5 0q2.5 1.5 5 0t5 0q2.25 1.5 4.5 0m-19 3.5q2.25-1.5 4.5 0q2.5 1.5 5 0t5 0q2.25 1.5 4.5 0");
}

</style>
