<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ddgawbqpo"/><path class="t6vq_mb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:amber-stone" /></template>
<style>
.ddgawbqpo {
  d: path("M2.5 12a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

.t6vq_mb9u {
  d: path("M7.25 10.25a5 5 0 0 1 3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
