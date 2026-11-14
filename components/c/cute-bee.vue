<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hkas22bvk"/><path class="sdq07tbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cute-bee" /></template>
<style>
.hkas22bvk {
  d: path("M4 14.5a7.5 5.5 0 1 0 15 0a7.5 5.5 0 1 0-15 0Z");
}

.sdq07tbkd {
  d: path("M11.5 9c-2-5-5-6.5-5.5-4.5C5.75 6 8.5 8 11.5 9Zm0 0c2-5 5-6.5 5.5-4.5C17.25 6 14.5 8 11.5 9Zm7.5 5.5h2.5m-13-5v10m6-10v10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
