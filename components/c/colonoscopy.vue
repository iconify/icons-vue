<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qo8giabun"/><path class="g_er6obuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colonoscopy" /></template>
<style>
.g_er6obuh {
  fill: currentColor;
  d: path("M18 10a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.qo8giabun {
  d: path("M3 19.5Q1.5 17.75 3 16q-1.5-1.75 0-3.5Q1.5 10.75 3 9Q1.5 7.25 3 5.5c0-2 1.25-3 3-3q2-1 4 0q2-1 4 0q2-1 4 0c1.75 0 3 1 3 3q1.5 1.75 0 3.5q1.5 1.75 0 3.5q1.5 1.75 0 3.5q1.5 1.75 0 3.5h-4v-11c0-1.25-.75-2-2-2H9c-1.25 0-2 .75-2 2v11Zm16 2.25V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
