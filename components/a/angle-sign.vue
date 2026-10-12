<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mugk83bdr"/><path class="p25zpgboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:angle-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mugk83bdr {
  d: path("M19 4.75L4.25 19.25h15.5");
}

.p25zpgboi {
  d: path("M11 19.25a6.75 6.75 0 0 0-1.94-4.73");
}

</style>
