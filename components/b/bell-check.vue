<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipof0itfh"/><path class="d2kfp99zt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bell-check" /></template>
<style>
.d2kfp99zt {
  d: path("m9.5 11.5l1.75 1.75L14.5 10");
}

.ipof0itfh {
  d: path("M6 10.5a6 6 0 0 1 12 0v4l1.5 2.25c.35.5.1 1.25-.5 1.25H5c-.6 0-.85-.75-.5-1.25L6 14.5Zm6-8v2M10 21h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
