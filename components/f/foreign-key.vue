<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o962wq6_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foreign-key" /></template>
<style>
.o962wq6_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7-3L19.5 4m-2.75 2.75L19 9m-4.75.25l2 2M7 16.5h.01m8.74 1.25l-.25.25a1.75 1.75 0 0 0 2.5 2.5l.25-.25m-.5-4.5l.25-.25a1.75 1.75 0 0 1 2.5 2.5l-.25.25M17 19l2-2");
}

</style>
