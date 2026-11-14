<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifrtmqgtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-dance-marathon" /></template>
<style>
.ifrtmqgtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0V3m0 0q5.5 1 6 6.5m1.5 12l-3.25-3.25A2 2 0 0 1 18 16a2 2 0 0 1 3.25 2.25Z");
}

</style>
