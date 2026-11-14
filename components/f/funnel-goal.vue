<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g545it0iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:funnel-goal" /></template>
<style>
.g545it0iz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h16l-6.75 5v2h-2.5v-2ZM3 17a9 4.25 0 1 0 18 0a9 4.25 0 1 0-18 0Zm9 0h.01");
}

</style>
