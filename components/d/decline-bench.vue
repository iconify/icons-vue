<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x9aemcpxb"/><path class="yivntmbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:decline-bench" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9aemcpxb {
  d: path("m4.156 11.434l15.688-5.368A1.25 1.25 0 0 1 21.5 7.25a2.45 2.45 0 0 1-1.656 2.316L4.156 14.934A1.25 1.25 0 0 1 2.5 13.75a2.45 2.45 0 0 1 1.656-2.316M4.5 19.5H7V14");
}

.yivntmbbl {
  d: path("M14.5 19.5H17v-9m-10 9h2.5m7.5 0h2.5");
}

</style>
