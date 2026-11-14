<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccgzn4w5y"/><path class="nkll69bez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-sitting" /></template>
<style>
.ccgzn4w5y {
  d: path("M12.5 9.5L13 5q.25-1.5 1.75-1.5h1.75l4 3v2.25H17V21H7.5c-2.5 0-2.5-6 1-8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkll69bez {
  d: path("M14 4q-2 2-1.75 5.25M6.5 21H3.75a1.5 1.5 0 0 1-1.25-2.5m14.25-12h.01");
}

</style>
