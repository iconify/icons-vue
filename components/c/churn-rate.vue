<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_dqd4b7d"/><path class="wpg74zbxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:churn-rate" /></template>
<style>
.j_dqd4b7d {
  d: path("M2.5 5h14L15 20.5H4Zm1 4.5h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpg74zbxi {
  fill: currentColor;
  d: path("M19 13c.75 1 1.25 1.75 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.5.5-1.25 1.25-2.25Zm1.25 5c.75 1 1.25 1.75 1.25 2.25a1.25 1.25 0 0 1-2.5 0c0-.5.5-1.25 1.25-2.25Z");
}

</style>
