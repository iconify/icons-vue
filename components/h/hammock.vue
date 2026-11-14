<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nlfj-2b-b"/><path class="qrl6ul59e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hammock" /></template>
<style>
.nlfj-2b-b {
  d: path("M3 4v17M21 4v17M3 8l3 3c3 4.5 9 4.5 12 0l3-3");
}

.qrl6ul59e {
  d: path("M6 11c3 1.75 9 1.75 12 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
