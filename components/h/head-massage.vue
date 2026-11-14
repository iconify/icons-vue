<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2s-e2bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:head-massage" /></template>
<style>
.g2s-e2bqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 20.5v-3c-2-1.5-3-3.5-3-5C5.5 9.25 8 7 11.5 7c3 0 5.5 2 5.5 5l1.25 2.5c.25.5 0 .75-.5.75H17v1.5c0 .75-.5 1.25-1.25 1.25H14.5v2.5M2.798 10.235a8.75 8.75 0 0 1 2.828-4.438m2.631-1.519a8.75 8.75 0 0 1 5.986 0m2.631 1.519a8.75 8.75 0 0 1 2.828 4.438");
}

</style>
