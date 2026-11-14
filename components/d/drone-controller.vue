<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yigynj7zx"/><path class="l4-h4ibow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-controller" /></template>
<style>
.l4-h4ibow {
  d: path("M10 10.25h4v3h-4ZM5.5 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm10 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yigynj7zx {
  d: path("M3.5 7.5h17a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-12a1 1 0 0 1 1-1Zm3 0L5 3m12.5 4.5L19 3");
}

</style>
