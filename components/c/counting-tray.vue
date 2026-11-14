<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="iwagbibar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counting-tray" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.iwagbibar {
  d: path("M5.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.5 0h.01m3.49 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-8.5 5h.01m3.49 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.5 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
