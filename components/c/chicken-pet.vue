<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lpdpo5b4a"/><path class="tocvggbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chicken-pet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpdpo5b4a {
  d: path("M5.5 8c0-4 4.5-4 4.5-.5c0 2.5 2 3 5 2.5c1.5-.5 3-2.5 4-4.5c1.75 3 1.75 7-.5 9.25C16 17 9 17 6.5 14c-1.5-2-1-4-1-6");
}

.tocvggbmn {
  d: path("m5.5 7l-2 1l2 1m5.5 7.5v4m3.5-4v4m-11 0h17M8 7.25h.01");
}

</style>
