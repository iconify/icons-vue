<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="m8j2cw4ii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goal-tile-02" /></template>
<style>
.b1giyo3pl {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8j2cw4ii {
  d: path("M2.5 18C6 18 8 13.5 12 13.5s6 4.5 9.5 4.5M12 13.5v-8m2.125.974l.9.412a1.5 1.5 0 0 1 0 2.728l-.9.412A1.5 1.5 0 0 1 12 8.662v-.824a1.5 1.5 0 0 1 2.125-1.364");
}

</style>
