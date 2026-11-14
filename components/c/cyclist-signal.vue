<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="gbqs1ibse"/><path class="gevuqab-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cyclist-signal" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.gbqs1ibse {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-3.25 8.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.gevuqab-k {
  d: path("m8.75 16.25l1.5-3.25h3.5l1.5 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
