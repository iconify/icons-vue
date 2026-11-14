<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziskhy4-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-check" /></template>
<style>
.ziskhy4-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 15l5.5 5.5L17 12m1-10q0 3.5 3.5 3.5Q18 5.5 18 9q0-3.5-3.5-3.5Q18 5.5 18 2Z");
}

</style>
