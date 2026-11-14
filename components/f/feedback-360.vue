<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umawoe4ex"/><path class="uwd6k7b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feedback-360" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umawoe4ex {
  d: path("M21.176 9.541a9.5 9.5 0 1 1-2.458-4.259");
}

.uwd6k7b7u {
  d: path("M16.25 5.25h2.5v-2.5M9 7h6a1.5 1.5 0 0 1 1.5 1.5V13a1.5 1.5 0 0 1-1.5 1.5h-3.5L9 16.75V14.5A1.5 1.5 0 0 1 7.5 13V8.5A1.5 1.5 0 0 1 9 7Z");
}

</style>
