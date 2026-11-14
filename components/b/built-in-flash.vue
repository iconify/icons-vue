<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocefyobnm"/><path class="xdb9dybao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:built-in-flash" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocefyobnm {
  d: path("M6 9h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 9m.021-3.064l4.458-1.372a1.005 1.005 0 0 0 .646-1.314a1.134 1.134 0 0 0-1.396-.686L5.271 3.936a1.005 1.005 0 0 0-.646 1.314a1.134 1.134 0 0 0 1.396.686");
}

.xdb9dybao {
  d: path("M10.5 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2-6V5.25");
}

</style>
