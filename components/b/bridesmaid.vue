<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4a-_ktdj"/><path class="sm2e5dbie"/><path class="gbqjzgizl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bridesmaid" /></template>
<style>
.gbqjzgizl {
  d: path("M9.25 11.25L12 15l2.75-3.75M12 15l-1.5 6m1.5-6l1.5 6M12 15l-3.5-1.5V17Zm0 0l3.5-1.5V17Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4a-_ktdj {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.sm2e5dbie {
  d: path("M4.25 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
