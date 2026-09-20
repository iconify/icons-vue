<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="wqx96pbyf"/><path class="p8hbe6atr"/><path class="uc38txb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-chart-outline-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8hbe6atr {
  d: path("M14 9v7.5");
}

.uc38txb3u {
  d: path("M8.5 16.5h7");
}

.wqx96pbyf {
  d: path("M10 12v4.5");
}

</style>
