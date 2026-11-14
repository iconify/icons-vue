<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z54ha3b8r"/><path class="uhcez2-_r"/><path class="j29wracxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-equity" /></template>
<style>
.j29wracxh {
  d: path("M4.5 17.25a7.5 2 0 0 0 15 0m-9-3.75v-3h3v3");
}

.uhcez2-_r {
  d: path("M4.5 15v4.5a7.5 2 0 0 0 15 0V15M5 8.5L12 3l7 5.5v5H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z54ha3b8r {
  d: path("M4.5 15a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0Z");
}

</style>
