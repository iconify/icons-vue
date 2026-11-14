<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i1ncreb8m"/><path class="lykzf-bih"/><path class="j4_8skbrh"/><path class="uypqojb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-arch" /></template>
<style>
.i1ncreb8m {
  d: path("M2 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.j4_8skbrh {
  d: path("M6 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4-1a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3 3a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.lykzf-bih {
  d: path("M3 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uypqojb4o {
  d: path("M18 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM4 15v6m16-6v6");
}

</style>
