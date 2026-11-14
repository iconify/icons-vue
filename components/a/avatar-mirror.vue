<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6wf5qb9m"/><path class="q90t0hx3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avatar-mirror" /></template>
<style>
.k6wf5qb9m {
  d: path("M6 19V8a6 6 0 0 1 12 0v11Zm2 0l-1.5 2.5M16 19l1.5 2.5");
}

.q90t0hx3v {
  d: path("M9.75 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1 7.5c0-2 1.5-2.75 3.25-2.75s3.25.75 3.25 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
