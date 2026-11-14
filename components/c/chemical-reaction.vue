<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4kgjzbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemical-reaction" /></template>
<style>
.z4kgjzbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM3 16a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 3 16Zm6.75-4h4.5m-2-2l2 2l-2 2m5.25-6A1.75 1.75 0 1 0 21 8a1.75 1.75 0 1 0-3.5 0Zm-.5 7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25-6v3.75");
}

</style>
