<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fi4qevbnv"/><path class="y4tvei9xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-board" /></template>
<style>
.fi4qevbnv {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18V6A3.5 3.5 0 0 1 6 2.5M2.5 7.75h19M5.5 5h.01m2.74 0h.01M11 5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4tvei9xi {
  d: path("M6 10.5h3.75a.75.75 0 0 1 .75.75v7.25a.75.75 0 0 1-.75.75H6a.75.75 0 0 1-.75-.75v-7.25A.75.75 0 0 1 6 10.5m-.75 1.75h5.25m-3.75 2.5h2m-2 2.25h1m6.5-6.5H18a.75.75 0 0 1 .75.75v7.25a.75.75 0 0 1-.75.75h-3.75a.75.75 0 0 1-.75-.75v-7.25a.75.75 0 0 1 .75-.75m-.75 1.75h5.25M15 14.75h2M15 17h1");
}

</style>
