<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv-p5pgik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jury-duty" /></template>
<style>
.zv-p5pgik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-4 0h8M3.5 6.5h17m-15 0L2.75 13M5.5 6.5L8.25 13m-5.75.5h6a3 2.5 0 0 1-6 0Zm16-7L15.75 13m2.75-6.5l2.75 6.5m-5.75.5h6a3 2.5 0 0 1-6 0Z");
}

</style>
