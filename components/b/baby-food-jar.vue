<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y01lsl9cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-food-jar" /></template>
<style>
.y01lsl9cr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14v4.5H5Zm1.5 4.5V9q-2 1-2 3.5v6A2.5 2.5 0 0 0 7 21h10a2.5 2.5 0 0 0 2.5-2.5v-6q0-2.5-2-3.5V7.5M4.5 13h15m-15 4.5h15");
}

</style>
