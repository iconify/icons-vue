<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pkdehphyr"/><path class="dos33lm6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breathalyser" /></template>
<style>
.dos33lm6w {
  d: path("M9.75 10.25h5v4h-5Zm2.5 7.75h.01");
}

.pkdehphyr {
  d: path("M7 7.5h10.5v14H7Zm3.5-5H14v5h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
