<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hm0i8ohim"/><path class="qmqc3ghwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:id-card-plus" /></template>
<style>
.hm0i8ohim {
  d: path("M6.875 8h6.25a4.375 4.375 0 0 1 4.375 4.375v3.75a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 2.5 16.125v-3.75A4.375 4.375 0 0 1 6.875 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmqc3ghwc {
  d: path("M5.25 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6.25 0h3m-9 4.5h9m4.75-15.25v5m-2.5-2.5h5");
}

</style>
