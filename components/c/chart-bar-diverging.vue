<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_jfkcbaa"/><path class="w0mgbzbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-bar-diverging" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_jfkcbaa {
  d: path("M12 2.5v19");
}

.w0mgbzbsb {
  fill: currentColor;
  d: path("M12.875 4h5.75a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-5.75A.875.875 0 0 1 12 4.875A.875.875 0 0 1 12.875 4m-6.5 4.75h4.75a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-4.75a.875.875 0 0 1-.875-.875a.875.875 0 0 1 .875-.875m6.5 4.75h3.25a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-3.25a.875.875 0 0 1-.875-.875a.875.875 0 0 1 .875-.875m-8.5 4.75h6.75a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-6.75a.875.875 0 0 1-.875-.875a.875.875 0 0 1 .875-.875");
}

</style>
