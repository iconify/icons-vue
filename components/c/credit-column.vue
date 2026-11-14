<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezg9e7bsd"/><path class="lwhea-tiu"/><path class="iqd8hj7pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:credit-column" /></template>
<style>
.ezg9e7bsd {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5m1.875 0v19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqd8hj7pe {
  d: path("M4.5 9h6.25M4.5 15h6.25");
}

.lwhea-tiu {
  fill: currentColor;
  d: path("M15.125 5.5za1.625 1.625 0 0 1 1.625 1.625v9.75a1.625 1.625 0 0 1-1.625 1.625a1.625 1.625 0 0 1-1.625-1.625v-9.75A1.625 1.625 0 0 1 15.125 5.5");
}

</style>
