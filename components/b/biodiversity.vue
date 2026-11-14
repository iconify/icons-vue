<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="czlimrw7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biodiversity" /></template>
<style>
.czlimrw7o {
  d: path("M6.5 15.5c-.5-4 1-6.5 4.25-7.25c.5 3.75-1 6.5-4.25 7.25Zm7-3.5c1.25-2.25 3-2.25 3.75 0l1.5-1.5v3l-1.5-1.5c-.75 2.25-2.5 2.25-3.75 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
