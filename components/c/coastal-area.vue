<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a507n1blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coastal-area" /></template>
<style>
.a507n1blq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18c3-3 6-3 9 0s6 3 9 0M3 12c3-3 6-3 9 0s6 3 9 0m-6-6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
