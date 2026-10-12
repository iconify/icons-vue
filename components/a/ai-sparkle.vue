<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbjscl9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-sparkle" /></template>
<style>
.sdbjscl9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7.25q.84 6.16 7 7q-6.16.84-7 7q-.84-6.16-7-7q6.16-.84 7-7M18 2.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25M18.5 16q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25q-.27-1.98-2.25-2.25q1.98-.27 2.25-2.25");
}

</style>
