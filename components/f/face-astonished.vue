<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dyjajybzl"/><path class="jcbwnmbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-astonished" /></template>
<style>
.dyjajybzl {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm4.75-5.25l2.5-1m7 1l-2.5-1");
}

.jcbwnmbdl {
  d: path("M7.25 10.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3.75 6a2 2.25 0 1 0 4 0a2 2.25 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
