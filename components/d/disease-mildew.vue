<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dvdwz3t4q"/><path class="hb42dqepe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disease-mildew" /></template>
<style>
.dvdwz3t4q {
  d: path("M12 2.5c7.5 3.5 8.5 11 0 17c-8.5-6-7.5-13.5 0-17Zm0 4v15");
}

.hb42dqepe {
  d: path("M6.5 9.5q1.75-2 3 0q1.25-2 2.5 0q1.25-2 2.5 0q1.25-2 3 0m-8.25 3.25h.01m5.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
