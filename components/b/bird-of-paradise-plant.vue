<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j2zlxj4wd"/><path class="a8f9typpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bird-of-paradise-plant" /></template>
<style>
.a8f9typpk {
  d: path("M7 12.75L4.5 4.5l5.5 8m0 0L14 4l.5 8.25");
}

.j2zlxj4wd {
  d: path("M7.5 14.75v6.75m-3-8.5l16-1.5C16 16 9 16.5 4.5 13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
