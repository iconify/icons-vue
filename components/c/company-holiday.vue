<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izifro-7c"/><path class="n35chtbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:company-holiday" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izifro-7c {
  d: path("M9.75 11.25h4.5A1.75 1.75 0 0 1 16 13v6.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 19.75V13a1.75 1.75 0 0 1 1.75-1.75m4 5.25h.01M2.5 2.5q9.5 4.5 19 0");
}

.n35chtbdh {
  d: path("M5.75 3.75za1.33 1.33 0 0 1 .75 1.892l-.125.233a.759.759 0 0 1-1.396-.146l-.283-.962A.826.826 0 0 1 5.75 3.75m4.75.875za1.085 1.085 0 0 1 .907 1.508l-.157.367a.789.789 0 0 1-1.457-.018l-.234-.584a.93.93 0 0 1 .941-1.273m3 0za.93.93 0 0 1 .941 1.273l-.234.584a.789.789 0 0 1-1.457.018l-.157-.367a1.085 1.085 0 0 1 .907-1.508m4.75-.875za.826.826 0 0 1 1.054 1.017l-.283.962a.759.759 0 0 1-1.396.146l-.125-.233a1.33 1.33 0 0 1 .75-1.892");
}

</style>
