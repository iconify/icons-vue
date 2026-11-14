<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcuqztv3m"/><path class="b5q2rwb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:built-in-flash" /></template>
<style>
.b5q2rwb2w {
  d: path("M10.5 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-2-6V5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcuqztv3m {
  d: path("M2.5 9h19v12h-19ZM5 6.25l6.5-2l-.75-2l-6.5 2Z");
}

</style>
