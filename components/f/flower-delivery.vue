<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jtqmcqgot"/><path class="q4-a95oll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-delivery" /></template>
<style>
.jtqmcqgot {
  d: path("M2.5 3v2.75a2.5 2.5 0 0 0 5 0V3L6.25 4.5L5 3L3.75 4.5Zm8 0v2.75a2.5 2.5 0 0 0 5 0V3l-1.25 1.5L13 3l-1.25 1.5Zm.485 11.11L8.5 20.5l-3.5-9h7l-.072.186M5 8.25l2 3.25m6-3.25l-3 3.25m3.75 7.75V14.5h4.5v1.75h2l1.25 1.5v1.5Z");
}

.q4-a95oll {
  d: path("M14.25 20.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
