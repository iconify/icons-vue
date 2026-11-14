<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpkv-s9rb"/><path class="thleaiz2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-girl-dress" /></template>
<style>
.fpkv-s9rb {
  d: path("M8.5 3q3.5 3 7 0q.25 3.75 2.25 5L17 11l3.5 10h-17L7 11l-.75-3q2-1.25 2.25-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.thleaiz2s {
  d: path("M11.5 10.5a1 1 0 1 1 1 0a1 1 0 1 1 0 1a1 1 0 1 1-1 0a1 1 0 1 1 0-1");
}

</style>
