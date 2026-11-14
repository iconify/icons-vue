<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r0zjojbfm"/><path class="zyk0edb-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cowshed" /></template>
<style>
.r0zjojbfm {
  d: path("M2.5 10L12 4l9.5 6v10.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyk0edb-v {
  d: path("m10.5 16l-.5-3a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 .5.5l-.5 3m-4 0h5v2.75h-5Zm.5-2.5c-.93.16-1.83-.06-2.25-.75c.65-.44 1.55-.44 2.25 0m4 .75c.93.16 1.82-.06 2.25-.75c-.65-.44-1.55-.44-2.25 0m-3-.25c-.12-.75-.35-1.2-1-1.5m3.25 1.5c-.12-.75.1-1.2.75-1.5");
}

</style>
