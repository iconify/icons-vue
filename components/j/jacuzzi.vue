<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5_-m0bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jacuzzi" /></template>
<style>
.r5_-m0bbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19v2a5 5 0 0 1-5 5h-9a5 5 0 0 1-5-5Zm4 7L6 21.5M17.5 19l.5 2.5M6 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.5-2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.25 3a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM8.5 3a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
