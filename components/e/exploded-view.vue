<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nffvmxb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exploded-view" /></template>
<style>
.nffvmxb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8V4.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2V8Zm-1 8h17v3.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2Zm8.5-5.25v.5m0 1.5v.5");
}

</style>
