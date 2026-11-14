<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_app_r9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-first-tooth" /></template>
<style>
.i_app_r9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5c0-3.75 3.25-4.75 5.25-3.5c.75.5 1.75.5 2.5 0c2-1.25 5.25-.25 5.25 3.5c0 2.75-1.25 4.25-1.75 6.5L13 19.5c-.25 1.5-1.75 1.5-2 0l-.75-4c-.25-1.25-2.25-1.25-2.5 0l-.75 4c-.25 1.5-1.75 1.5-2 0L4.25 14c-.5-2.25-1.75-3.75-1.75-6.5Zm16.5 8q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

</style>
