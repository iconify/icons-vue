<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ce1fnvbmu"/><path class="bhzswt-bg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kitchen-scale" /></template>
<style>
.bhzswt-bg {
  d: path("M8.5 14a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5 0l1.5-2M8 5h8");
}

.ce1fnvbmu {
  d: path("M7.875 8h8.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 16.125 20h-8.25A4.375 4.375 0 0 1 3.5 15.625v-3.25A4.375 4.375 0 0 1 7.875 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
