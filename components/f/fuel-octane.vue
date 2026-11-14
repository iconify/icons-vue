<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kw3no5bog"/><path class="ru7palwib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fuel-octane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kw3no5bog {
  d: path("M7 3h4a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6.5A3.5 3.5 0 0 1 7 3");
}

.ru7palwib {
  d: path("M6.25 9.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m8.25 4.25H16a1.5 1.5 0 0 1 1.5 1.5v3a1.75 1.75 0 0 0 3.5 0V8l-2.5-2.5M9 9.25l2-2");
}

</style>
