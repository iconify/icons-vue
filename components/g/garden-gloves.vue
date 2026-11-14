<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejopx51ap"/><path class="qzhakfw9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-gloves" /></template>
<style>
.ejopx51ap {
  d: path("M10.5 18v-4.5L8.25 11a1.75 1.75 0 0 1 2-2l.25.25V9A4.25 4.25 0 0 1 19 9v9m-7.75 0h7A1.75 1.75 0 0 1 20 19.75a1.75 1.75 0 0 1-1.75 1.75h-7a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 11.25 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzhakfw9y {
  d: path("M13.25 5A4.25 4.25 0 0 0 5 6.75v9.75m5.5 0H5a1 1 0 0 0-1 1V19a1 1 0 0 0 1 1h4.5m4-15v4m2.75-4v4m-8.5-6.25v4");
}

</style>
