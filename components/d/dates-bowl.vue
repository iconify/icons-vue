<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jn6xo5wqw"/><path class="yc0zwqbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dates-bowl" /></template>
<style>
.jn6xo5wqw {
  d: path("M2.5 12.5h19c0 4.5-4 7.5-9.5 7.5s-9.5-3-9.5-7.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc0zwqbox {
  d: path("M10 8.25a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0ZM3.5 9.5a2 3.5 0 1 0 4 0a2 3.5 0 1 0-4 0Zm13 0a2 3.5 0 1 0 4 0a2 3.5 0 1 0-4 0Z");
}

</style>
