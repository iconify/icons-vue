<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dll46s03a"/><path class="wg7zywb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clipboard-paste" /></template>
<style>
.dll46s03a {
  d: path("M8 21H6.5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wg7zywb3w {
  d: path("M11 10h9v11.5h-9ZM8.5 3h7v4.5h-7ZM14 14h3m-3 3.5h3");
}

</style>
