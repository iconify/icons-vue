<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qz56hnb8q"/><path class="eue7xx83f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autumn-calendar" /></template>
<style>
.eue7xx83f {
  d: path("m12 9l1.5 3l3.75-.75l-1.5 2.75l.25 1.75l-3.25-.5L12 16.5l-.75-1.25l-3.25.5l.25-1.75l-1.5-2.75l3.75.75Zm0 7.5v1.75");
}

.qz56hnb8q {
  d: path("M3.5 4.5h17V21h-17Zm4.5-2v4m8-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
