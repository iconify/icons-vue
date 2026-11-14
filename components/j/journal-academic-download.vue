<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zc7-_3t7w"/><path class="f1ha8jb-a"/><path class="e5a5z-n0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-academic-download" /></template>
<style>
.e5a5z-n0w {
  d: path("M12 8v2.5q2 1.25 4 0V8m2 6.5v7m-3-3l3 3l3-3");
}

.f1ha8jb-a {
  d: path("m14 5.5l3.25 1.75L14 9l-3.25-1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zc7-_3t7w {
  d: path("M14.1 21.5H4v-19h16v9.2M7.5 2.5v19");
}

</style>
