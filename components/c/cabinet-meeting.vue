<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j5fh86-7u"/><path class="wvh2n2bll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cabinet-meeting" /></template>
<style>
.j5fh86-7u {
  d: path("M9 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6.5 19c0-3.5 2.25-5.25 5.5-5.25s5.5 1.75 5.5 5.25m-15-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvh2n2bll {
  d: path("M2.5 19h19m-19 0c0-2 1-3.25 2-3.25s1.75.5 2.25 1.25m14.75 2c0-2-1-3.25-2-3.25s-1.75.5-2.25 1.25");
}

</style>
