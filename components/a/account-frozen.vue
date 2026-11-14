<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qwbaqippt"/><path class="ehvnz9bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-frozen" /></template>
<style>
.ehvnz9bfs {
  d: path("m16.25 14l1.25 1l1.25-1m1.25.75l-.25 1.5l1.25.5m0 1.5l-1.25.5l.25 1.5m-1.25.75l-1.25-1l-1.25 1M15 20.25l.25-1.5l-1.25-.5m0-1.5l1.25-.5l-.25-1.5");
}

.qwbaqippt {
  d: path("M11.9 21.5H4.5v-19h15v8m-11-8v19m3-14.5h4m2 14.5v-8m-3.5 6l7-4m-7 0l7 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
