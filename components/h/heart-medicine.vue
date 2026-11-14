<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2z577bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-medicine" /></template>
<style>
.h2z577bxl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.55 20.6q-5.178-3.883-7.108-6.037Q1.75 11.561 1.75 8.5v-.026q.156-4.5 4.562-5.427Q10.026 2.265 12 5.023q1.974-2.758 5.688-1.976q4.406.927 4.562 5.427V8.5q0 3.061-2.692 6.063q-1.93 2.154-7.108 6.037q-.048.036-.102.064t-.111.048q-.057.019-.117.028t-.12.01q-.06 0-.12-.01q-.06-.009-.117-.028t-.111-.048q-.054-.028-.102-.064m-1.494-10.044L8.642 11.97q-1.944 1.944 0 3.888t3.888 0l1.414-1.414l1.414-1.414q1.944-1.944 0-3.888t-3.888 0z");
}

</style>
