<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n31ubla9o"/><path class="j40-1f_nc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-floe" /></template>
<style>
.j40-1f_nc {
  d: path("M2.5 13.5q2.375-1 4.75 0t4.75 0t4.75 0t4.75 0M5 18.5q2.375-1 4.75 0t4.75 0t4.75 0");
}

.n31ubla9o {
  d: path("M7.25 13.5L9 7.5L12.5 5l4.25 8.5M12.5 5l-.75 8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
