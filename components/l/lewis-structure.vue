<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e144q-9cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lewis-structure" /></template>
<style>
.e144q-9cz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11-11a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-4.25 8.25l5.5-5.5m-6.5 1.5h.01m2.49-2.5h.01");
}

</style>
