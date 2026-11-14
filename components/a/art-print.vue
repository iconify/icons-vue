<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oi6zdub0w"/><path class="qxt0rovsm"/><path class="js1g62eyn"/><path class="ax1yrr41w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-print" /></template>
<style>
.ax1yrr41w {
  d: path("m7.5 18.75l2.75-4.25L13 18.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.js1g62eyn {
  d: path("M6.75 8.25h7a1.5 1.5 0 0 1 1.5 1.5v7.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5v-7.5a1.5 1.5 0 0 1 1.5-1.5");
}

.oi6zdub0w {
  d: path("M10 5.5v-3h11.5V14H18");
}

.qxt0rovsm {
  d: path("M5.125 5.5h10.25A2.625 2.625 0 0 1 18 8.125v10.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875V8.125A2.625 2.625 0 0 1 5.125 5.5");
}

</style>
