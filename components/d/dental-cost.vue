<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hwomh0bxy"/><path class="smze0hysz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-cost" /></template>
<style>
.hwomh0bxy {
  d: path("m12 2.5l6.5 6v13h-13v-13Z");
}

.smze0hysz {
  d: path("M10.75 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-1.75 6c0-2 1.5-2.5 3-1.75c1.5-.75 3-.25 3 1.75c0 1.75-.75 2.75-1 4l-.5 1.75L12 17l-1.5 2.5l-.5-1.75c-.25-1.25-1-2.25-1-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
