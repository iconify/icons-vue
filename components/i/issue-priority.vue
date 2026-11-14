<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quyy_r0lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:issue-priority" /></template>
<style>
.quyy_r0lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm7-4.5v6m0 3h.01m3.99-9v6m0 3h.01");
}

</style>
