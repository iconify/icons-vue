<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ax_msvt1o"/><path class="pdkejgsnv"/><path class="f7pi1hbcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inpatient" /></template>
<style>
.ax_msvt1o {
  d: path("M11.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.49 0 .963.039M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.f7pi1hbcj {
  fill: currentColor;
  d: path("M15.75 15.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.pdkejgsnv {
  d: path("m8 14.5l2.5 2.5l.965-.965M7 18h.01m7.24-4v7.75m0-4.5h7.5V20h-7.5ZM21.5 20v1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
