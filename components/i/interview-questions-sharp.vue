<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mz3y6c41u"/><path class="kv43q2wlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:interview-questions-sharp" /></template>
<style>
.kv43q2wlw {
  d: path("M3.5 20.25h8.75v-.75c0-2.9-2.25-5-4.75-5s-4.75 2.1-4.75 5v.75zm11.75-17.5h6v7H16.5l-2.5 2V9.7l-1.72-.216l-.03-1.734v-5h2Z");
}

.mz3y6c41u {
  cx: 7.5px;
  cy: 9.5px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
