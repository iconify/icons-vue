<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ctu5modtj"/><path class="jwljcdc3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:human-rights" /></template>
<style>
.ctu5modtj {
  d: path("M5.5 15.25v-8a1.5 1.5 0 0 1 3 0v-2.5a1.5 1.5 0 0 1 3 0v-.5a1.5 1.5 0 0 1 3 0v1a1.5 1.5 0 0 1 3 0V13l1.25-1.25a1.4 1.4 0 0 1 1.98 1.98L17 18.05a6 6 0 0 1-4.75 3.2h-.75a6 6 0 0 1-6-6m3-7.5V11m3-5.75V11m3-5.25V11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwljcdc3u {
  d: path("M11.5 18.5c-1.75-1.15-2.75-2.25-2.75-3.4a1.375 1.375 0 0 1 2.75-.35a1.375 1.375 0 0 1 2.75.35c0 1.15-1 2.25-2.75 3.4");
}

</style>
