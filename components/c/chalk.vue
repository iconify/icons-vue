<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmsx7wbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chalk" /></template>
<style>
.vmsx7wbhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.3 11.88l8.08-8.08q.71-.71 1.42 0l1.4 1.4q.71.71 0 1.42l-8.08 8.08q-.71.71-1.42 0l-1.4-1.4q-.71-.71 0-1.42m-4.05 7.87c2-1.5 3.5-1.5 5 0s3.5 1.5 5 0s3.5-1.5 5 0");
}

</style>
