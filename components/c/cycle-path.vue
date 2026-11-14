<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chbr5ccml"/><path class="wqo5-vbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cycle-path" /></template>
<style>
.chbr5ccml {
  d: path("M3 13a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m11 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqo5-vbpp {
  d: path("M6.5 13H12l3-6l2.5 6M12 13L9.5 7M8 7h3m4 0l-.5-2h2M2 21.5q10-4.5 20 0");
}

</style>
