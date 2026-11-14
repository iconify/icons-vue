<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="irbudsb2w"/><path class="hvexjkbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-current" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvexjkbco {
  d: path("M2.25 15.25L4.5 13l2.25 2.25m10.5-4.5L19.5 13l2.25-2.25");
}

.irbudsb2w {
  d: path("M10.5 5.5h-6v15h15v-15h-6m-3-2.5v5m3-3.75v2.5");
}

</style>
