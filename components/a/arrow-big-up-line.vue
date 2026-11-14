<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqh2w7_ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-big-up-line" /></template>
<style>
.wqh2w7_ek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 20.5h6M13.547 4.547l4.039 4.039A.828.828 0 0 1 17 10a2 2 0 0 0-2 2v1.813A2.19 2.19 0 0 1 12.813 16h-1.625A2.19 2.19 0 0 1 9 13.813V12a2 2 0 0 0-2-2a.828.828 0 0 1-.586-1.414l4.039-4.039a2.19 2.19 0 0 1 3.094 0");
}

</style>
