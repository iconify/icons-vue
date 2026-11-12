<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trf-iy3jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-square-fill-sharp" /></template>
<style>
.trf-iy3jw {
  fill: currentColor;
  d: path("M7 2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm14.342 11.06a1.002 1.002 0 0 1 .029 1.868l-4.602 1.841l-1.841 4.602a1 1 0 0 1-1.868-.029l-4-11a1 1 0 0 1 1.282-1.282Z");
}

</style>
