<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdau0rq1w"/><path class="uvnx9sh3k"/><path class="gxfnifbgh"/><path class="tdqo1wtow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corner-lot" /></template>
<style>
.gxfnifbgh {
  d: path("M21.5 2.5v19h-19M19 4v2.5m0 3V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdau0rq1w {
  fill: currentColor;
  d: path("M4.25 2.5h8A1.75 1.75 0 0 1 14 4.25v8A1.75 1.75 0 0 1 12.25 14h-8a1.75 1.75 0 0 1-1.75-1.75v-8A1.75 1.75 0 0 1 4.25 2.5");
}

.tdqo1wtow {
  d: path("M19 15v4h-4m-3 0H9.5m-3 0H4");
}

.uvnx9sh3k {
  d: path("M16.5 2.5v14h-14");
}

</style>
