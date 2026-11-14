<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sp6ec3sqs"/><path class="dl-b2db8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farmers-walk" /></template>
<style>
.dl-b2db8k {
  d: path("M12 9.75V15l-2 6.5m2-6.5l2 6.5M3.5 16.25V14h3v2.25a2.75 2.75 0 1 1-3 0m14 0V14h3v2.25a2.75 2.75 0 1 1-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sp6ec3sqs {
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M5 14l3.5-4.25h7L19 14");
}

</style>
