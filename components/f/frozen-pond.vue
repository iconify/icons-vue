<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z920k880h"/><path class="gobhwybjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frozen-pond" /></template>
<style>
.gobhwybjh {
  d: path("m7.5 5.5l2.25 4L8 12l3.5 2.5l-1.5 4m4-5.5l2.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z920k880h {
  d: path("M2.5 12a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

</style>
