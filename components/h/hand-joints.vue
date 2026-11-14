<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8aca5vun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-joints" /></template>
<style>
.u8aca5vun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.5V6a1.5 1.5 0 0 1 3 0v6m0 0V4a1.5 1.5 0 0 1 3 0v8m0 0V5a1.5 1.5 0 0 1 3 0v7m0 0V7.5a1.5 1.5 0 0 1 3 0V15c0 4-2.75 6.5-6.5 6.5c-3 0-4.75-1.5-6.25-3.75L3.5 14.5A1.5 1.5 0 0 1 6 13l.5.5m3 1.5h.01m2.99 0h.01m2.99 0h.01");
}

</style>
