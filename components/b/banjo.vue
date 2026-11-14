<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wp43x8w0i"/><path class="jo3duhbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banjo" /></template>
<style>
.jo3duhbmt {
  d: path("M11.75 10.25L17 5l1.25-2.5l3.25 3.25L19 7l-5.25 5.25M6 15.5L8.5 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp43x8w0i {
  d: path("M2.5 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

</style>
