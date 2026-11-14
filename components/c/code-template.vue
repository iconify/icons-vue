<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6vaj69bs"/><path class="b5-0i23-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-template" /></template>
<style>
.b5-0i23-s {
  d: path("M10 11.5L7.5 14l2.5 2.5m4-5l2.5 2.5l-2.5 2.5");
}

.k6vaj69bs {
  d: path("M4.5 2.5h15v19h-15Zm3 3.5h3m3 0h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
