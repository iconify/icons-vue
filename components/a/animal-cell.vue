<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcuusfi0u"/><path class="y-ncvkb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-cell" /></template>
<style>
.fcuusfi0u {
  d: path("M11 2.5c5.5-.5 10.5 3 10.5 9s-4.5 10-10 10s-9-3.5-9-9s3-9.5 8.5-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-ncvkb3r {
  d: path("M6 10a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 6.25a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0Z");
}

</style>
