<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="lyd3o6epz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bubble-sheet" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.lyd3o6epz {
  d: path("M7 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM7 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-5.5 5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
