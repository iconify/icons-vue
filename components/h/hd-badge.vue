<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxgie-r8m"/><path class="ezv3tmubj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hd-badge" /></template>
<style>
.ezv3tmubj {
  d: path("M13.5 8.5H15a3.5 3.5 0 0 1 0 7h-1.5Z");
}

.kxgie-r8m {
  d: path("M2.5 5h19v14h-19Zm4 3.5v7m4-7v7m-4-3.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
