<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0ywq7jsc"/><path class="om4tbr29h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gaff-hook" /></template>
<style>
.g0ywq7jsc {
  d: path("m4 20.5l7-12.25c1.5-2.75 5-4.75 7-2.75C19.5 7 19 10 17 11");
}

.om4tbr29h {
  d: path("M17 11c3 2 3 5 0 7l2 3h-4l2-3c-3-2-3-5 0-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
