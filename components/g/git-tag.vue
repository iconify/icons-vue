<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5z5tqbkm"/><path class="qrmre7b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-tag" /></template>
<style>
.i5z5tqbkm {
  d: path("M9.5 5.5h11v13h-11l-4-6.5Z");
}

.qrmre7b3r {
  d: path("M9.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-7 0h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
