<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cb-5hebbx"/><path class="sdz7xmy1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:duck-pet" /></template>
<style>
.cb-5hebbx {
  d: path("M5 6.5a3 3 0 0 1 6 0C11 8 10.25 9 9.5 10h5c2 0 3.75-.5 5.75-2c.75 4.75-1.75 8.5-6.75 8.5H9c-3.5 0-5.5-2-5.5-4c0-1.5 1-2.25 3-2.5C5.5 9 5 8 5 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sdz7xmy1s {
  d: path("m4.152 6.86l-.027.015a.679.679 0 0 0 .026 1.201l.225.112a.692.692 0 0 0 .999-.688a.826.826 0 0 0-1.223-.64M8.5 6.25h.01M3.5 19.5H10m3 0h7.5");
}

</style>
