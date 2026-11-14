<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zr64otyni"/><path class="pstk-nb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple-juice" /></template>
<style>
.pstk-nb7w {
  d: path("M12 11c-1.75-1.25-3.75-.25-3.5 2.5s1.75 4.25 3.5 3.5c1.75.75 3.25-.75 3.5-3.5S13.75 9.75 12 11Zm0 0l1-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zr64otyni {
  d: path("M4.5 3h15L18 21.5H6Z");
}

</style>
