<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l41p6ur2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adopt-a-brick" /></template>
<style>
.l41p6ur2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 16h-10V9h14v3.6M2.5 9l4-4h14l-4 4m4-4v7l-.566.566M18.25 21.25L15.5 18.5a2 2 0 0 1 2.75-2.75A2 2 0 0 1 21 18.5Z");
}

</style>
