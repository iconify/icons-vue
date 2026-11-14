<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zziakns7n"/><path class="y26snsc_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:element-aluminium" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y26snsc_q {
  d: path("M5.5 11.5h9l2.5 6m-2.5-6l4-5");
}

.zziakns7n {
  d: path("m3 17.5l2.5-6l4-5h9l2.5 6l-4 5Z");
}

</style>
