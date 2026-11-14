<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ailmrqteb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb-on" /></template>
<style>
.ailmrqteb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15.5a5 5 0 1 1 6 0V18H9Zm1 5.25h4M12 2v1.75M4.5 5L6 6.5M19.5 5L18 6.5");
}

</style>
