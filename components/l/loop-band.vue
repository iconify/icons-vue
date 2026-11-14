<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ddgawbqpo"/><path class="yewhk9hma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loop-band" /></template>
<style>
.ddgawbqpo {
  d: path("M2.5 12a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yewhk9hma {
  d: path("M6.5 12a5.5 3.5 0 1 0 11 0a5.5 3.5 0 1 0-11 0ZM12 5v3.5");
}

</style>
