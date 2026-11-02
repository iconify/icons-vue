<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="unqjl3cbd"/><path class="auf36vbch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-tree-duocolor" /></template>
<style>
.auf36vbch {
  d: path("M8 6h12m-8 6h8m-8 6h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.unqjl3cbd {
  stroke-opacity: 0.4;
  d: path("M4 6v10a2 2 0 0 0 2 2h2m-4-6h4");
}

</style>
