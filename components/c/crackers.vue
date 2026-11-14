<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysfk4ibyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crackers" /></template>
<style>
.ysfk4ibyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1 0-5a3.5 3.5 0 0 1 0-5a3.5 3.5 0 0 1 0-5ZM9 9h.01M15 9h.01M9 15h.01M15 15h.01");
}

</style>
