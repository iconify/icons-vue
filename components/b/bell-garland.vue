<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qr6qwbcrg"/><path class="yu5xb2b3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bell-garland" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr6qwbcrg {
  d: path("M2.5 6q9.5 8 19 0M5 7.75V9.5m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0");
}

.yu5xb2b3m {
  d: path("M12 10v2m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0m6-9.25V9.5m-2.5 5c.75-1 .75-2 .75-3.25a1.75 1.75 0 0 1 3.5 0c0 1.25 0 2.25.75 3.25Zm1.5 0a1 1 0 0 0 2 0");
}

</style>
