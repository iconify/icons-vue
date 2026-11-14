<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0w6g1bkf"/><path class="j-ms01dkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:knowledge-sharing" /></template>
<style>
.j-ms01dkx {
  d: path("M10.5 13.5v-1c-1.25-.75-2-2-2-3.5a3.5 3.5 0 0 1 7 0c0 1.5-.75 2.75-2 3.5v1Z");
}

.q0w6g1bkf {
  d: path("M7 2.5h10A4.5 4.5 0 0 1 21.5 7v5.5A4.5 4.5 0 0 1 17 17h-6.5l-5 4v-4.5a4.5 4.5 0 0 1-3-4V7A4.5 4.5 0 0 1 7 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
