<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z50a626ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-vent-sharp" /></template>
<style>
.z50a626ue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h17.5v11.5H3.25zM7 7h10M7 10h10m-9.25 7.25l-1 1l1 1l1 1l-1 1m4.25-4l-1 1l1 1l1 1l-1 1m4.25-4l-1 1l1 1l1 1l-1 1");
}

</style>
