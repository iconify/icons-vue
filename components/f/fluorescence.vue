<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkmhqeb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fluorescence" /></template>
<style>
.rkmhqeb9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5V13l-5 8h14l-5-8V9.5M7.5 17h9M12 2.5v3.25M7 4l1.5 2M17 4l-1.5 2");
}

</style>
