<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xje4uvt4y"/><path class="gibbinwgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:axe" /></template>
<style>
.gibbinwgp {
  d: path("M16.25 6.25L14 2.75q-3.75.5-4.25 4.25L13 9.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xje4uvt4y {
  d: path("M17.968 6.532za1.5 1.5 0 0 1 0 2.122L6.654 19.968a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122L15.846 6.532a1.5 1.5 0 0 1 2.122 0");
}

</style>
