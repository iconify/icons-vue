<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3xz8sb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-collision" /></template>
<style>
.j3xz8sb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 9.5c0-2.75 1.5-4.25 3.5-4.25s3.5 1.5 3.5 4.25m6-9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 9.5c0-2.75 1.5-4.25 3.5-4.25s3.5 1.5 3.5 4.25m-18-17H10m-2-2l2 2l-2 2m12.5-2H14m2-2l-2 2l2 2");
}

</style>
