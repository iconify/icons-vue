<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qa_dsx20m"/><path class="f48cbdqmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leak-sensor" /></template>
<style>
.f48cbdqmk {
  d: path("M4.5 15v3a7.5 2.25 0 0 0 15 0v-3m-17 5.25h19M12 2.5q3 3 3 4.5a3 3 0 0 1-6 0q0-1.5 3-4.5Z");
}

.qa_dsx20m {
  d: path("M4.5 15a7.5 2.25 0 1 0 15 0a7.5 2.25 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
