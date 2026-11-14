<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w0qauib4d"/><path class="h_g-odqmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catalog" /></template>
<style>
.h_g-odqmx {
  d: path("M5.5 7H9v3.5H5.5Zm0 6.5H9V17H5.5ZM15 7h3.5v3.5H15Zm0 6.5h3.5V17H15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w0qauib4d {
  d: path("M12 5c-2-1.25-5.5-1.75-9.5-1.5v16c4-.25 7.5.25 9.5 1.5c2-1.25 5.5-1.75 9.5-1.5v-16c-4-.25-7.5.25-9.5 1.5Zm0 0v16");
}

</style>
