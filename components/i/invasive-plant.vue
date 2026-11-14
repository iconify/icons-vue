<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-3ei1b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invasive-plant" /></template>
<style>
.w-3ei1b8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V7m0 1.5C12 5.75 10.25 4 7.75 4c0 2.75 1.75 4.5 4.25 4.5ZM12 7c0-2.75 1.75-4.5 4.25-4.5C16.25 5.25 14.5 7 12 7Zm0 9.5c-3 0-7-1-8-4a2 2 0 0 1 4 0m4 1c3 0 7 1 8 4a2 2 0 0 1-4 0");
}

</style>
