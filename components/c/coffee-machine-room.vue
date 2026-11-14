<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vux54-pef"/><path class="wfp6attlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coffee-machine-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vux54-pef {
  d: path("M5.75 3h12.5A1.75 1.75 0 0 1 20 4.75v1.5A1.75 1.75 0 0 1 18.25 8h-8.5A1.75 1.75 0 0 0 8 9.75v6.5A1.75 1.75 0 0 0 9.75 18h8.75a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5.75A1.75 1.75 0 0 1 4 19.25V4.75A1.75 1.75 0 0 1 5.75 3");
}

.wfp6attlx {
  d: path("M12.5 11h5v1.5L19 16v2h-8v-2l1.5-3.5Z");
}

</style>
