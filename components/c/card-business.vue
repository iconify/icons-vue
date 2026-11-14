<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmcqwy6jj"/><path class="va1qwubla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-business" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmcqwy6jj {
  d: path("M6 7h9.25a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 7");
}

.va1qwubla {
  d: path("M5.5 4h14a2 2 0 0 1 2 2v10.5m-16 .5v-6.75h5V17ZM8 14.25V17m5.25-5.5H16m-2.75 3.25h2");
}

</style>
