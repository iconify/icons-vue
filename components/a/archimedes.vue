<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xy-oaab2i"/><path class="m2counbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:archimedes" /></template>
<style>
.m2counbfq {
  d: path("M9 7h6v8H9Zm-5 3h5m6 0h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xy-oaab2i {
  d: path("M4 4v15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4");
}

</style>
