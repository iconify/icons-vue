<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zwrwkibtx"/><path class="ttg95_-1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-rider" /></template>
<style>
.ttg95_-1e {
  d: path("M15 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwrwkibtx {
  d: path("M3 4.5h7v6H3Zm15 12l-3-12h-2m-9 9h13.25M4 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
