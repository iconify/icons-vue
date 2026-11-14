<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g00rdtk7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyword-cloud" /></template>
<style>
.g00rdtk7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.091 15.5H6.5c-2.25 0-4-1.75-4-4c0-2 1.5-3.75 3.5-4c.75-2.75 3.25-5 6.5-5c3.5 0 6.25 2.5 6.75 6c1.25.5 2.25 2 2.25 3.5c0 .317-.049.634-.142.94m.392 8.81h-4.5L14 18.5l4.5-4.5l3.25 3.25Zm-2.5-2.5h.01");
}

</style>
