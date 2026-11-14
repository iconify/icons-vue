<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gjzoqze8y"/><path class="unpeqgb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astronomy-class" /></template>
<style>
.gjzoqze8y {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unpeqgb5s {
  d: path("M2.5 12a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0M19 5h.01M5 19h.01");
}

</style>
