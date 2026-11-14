<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsbs92bno"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:court-fee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsbs92bno {
  d: path("M3 8.375za1.14 1.14 0 0 1 .528-.959l6.169-3.908a1.5 1.5 0 0 1 1.606 0l6.169 3.908a1.14 1.14 0 0 1 .528.959a.625.625 0 0 1-.625.625H3.625A.625.625 0 0 1 3 8.375M3 20.5h8.8m-5.8-9V17m4.5-5.5V17m4.5-5.5v1M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
