<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbq0bwb-m"/><path class="kc1yf3bro"/><path class="pqf31jbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-sphere" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc1yf3bro {
  d: path("M6.5 11a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.pqf31jbuh {
  d: path("M9.344 10.288a2.75 2.75 0 0 1 1.944-1.944");
}

.wbq0bwb-m {
  d: path("m3 9l1.5 11h15L21 9");
}

</style>
