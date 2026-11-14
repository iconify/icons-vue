<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rv7nk5rxi"/><path class="fpqdrwbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-smart-home" /></template>
<style>
.fpqdrwbwc {
  d: path("M7.327 13.264a3.75 3.75 0 0 1 3.409 3.409M7.632 9.778a7.25 7.25 0 0 1 6.59 6.59");
}

.rv7nk5rxi {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17ZM7 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
