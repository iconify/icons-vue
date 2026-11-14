<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipof0itfh"/><path class="g88_0r9zm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bell-user" /></template>
<style>
.g88_0r9zm {
  d: path("M10.5 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9.25 15c.45-1.2 1.45-2 2.75-2s2.3.8 2.75 2");
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
