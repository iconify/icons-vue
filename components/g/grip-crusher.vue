<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qez5enbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grip-crusher" /></template>
<style>
.qez5enbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 0l-3 8m7-8l3 8m-9.924.035za2 2 0 0 1 1.173 2.574l-1.751 4.683a2 2 0 0 1-2.574 1.173a2 2 0 0 1-1.173-2.574l1.751-4.683a2 2 0 0 1 2.574-1.173m9.848 0za2 2 0 0 1 2.574 1.173l1.751 4.683a2 2 0 0 1-1.173 2.574a2 2 0 0 1-2.574-1.173l-1.751-4.683a2 2 0 0 1 1.173-2.574M7.75 11l2-2.25L12 13l2.25-4.25l2 2.25");
}

</style>
