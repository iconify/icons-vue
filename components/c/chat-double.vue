<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-9dgdkyt"/><path class="j7ztdacox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-double" /></template>
<style>
.e-9dgdkyt {
  d: path("M3 9a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5.5a2 2 0 0 1-2 2H8.5l-3 3v-3H5a2 2 0 0 1-2-2Z");
}

.j7ztdacox {
  d: path("M9 7V5.5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
