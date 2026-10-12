<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="aqhok2bbj"/><path class="ff0-mne6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candy" /></template>
<style>
.aqhok2bbj {
  cx: 12px;
  cy: 12px;
  r: 4px;
}

.ff0-mne6v {
  d: path("M7.75 10.75L4 7.5a.75.75 0 0 0-1.25.55v7.9A.75.75 0 0 0 4 16.5l3.75-3.25Zm8.5 0L20 7.5a.75.75 0 0 1 1.25.55v7.9a.75.75 0 0 1-1.25.55l-3.75-3.25Zm-6-1.5c1.5 1 2.25 3.5 1.75 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
