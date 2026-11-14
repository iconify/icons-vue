<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy6n1qb4a"/><path class="zge__4byz"/><path class="oqs5mkv4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bone" /></template>
<style>
.oqs5mkv4z {
  d: path("M16.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8-7.5l7 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy6n1qb4a {
  d: path("M3.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.zge__4byz {
  d: path("M6 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
