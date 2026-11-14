<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="st43dpkaq"/><path class="y1ux6ccvy"/><path class="lehbqvbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circulatory-system" /></template>
<style>
.lehbqvbjj {
  d: path("m12 19.25l-1.5 1.25l1.5 1.25");
}

.st43dpkaq {
  d: path("M8 18s-5-3-5-6.25C3 10.25 4.25 9 5.75 9c1 0 1.75.75 2.25 1.5c.5-.75 1.5-1.5 2.25-1.5c1.5 0 2.75 1.25 2.75 2.75C13 15 8 18 8 18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1ux6ccvy {
  d: path("M10.5 9c0-4 2-6 5-6C19 3 21 6 21 10.5c0 5.5-4 10-10.5 10");
}

</style>
