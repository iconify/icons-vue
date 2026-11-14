<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="py984hb-m"/><path class="l3jxa-bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:isolated-danger-mark" /></template>
<style>
.l3jxa-bpr {
  fill: currentColor;
  d: path("M10.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.py984hb-m {
  d: path("M7 14h10l-2 4H9Zm5-3v3m-9 7h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
