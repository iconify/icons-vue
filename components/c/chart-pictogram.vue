<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hs6_w9bhe"/><path class="pb5tk7wda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-pictogram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs6_w9bhe {
  fill: currentColor;
  d: path("M3.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M2.5 19v-5.5a2.5 2.5 0 0 1 5 0V19Zm7.75-12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M9.5 19v-5.5a2.5 2.5 0 0 1 5 0V19Z");
}

.pb5tk7wda {
  d: path("M17.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-.75 12v-5.5a2.5 2.5 0 0 1 5 0V19Z");
}

</style>
