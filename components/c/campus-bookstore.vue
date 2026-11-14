<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olqai6pvw"/><path class="cy6nzyw5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-bookstore" /></template>
<style>
.cy6nzyw5f {
  d: path("M8 13.5c1.5-.75 3-.5 4 .5c1-1 2.5-1.25 4-.5V18c-1.5-.75-3-.5-4 .5c-1-1-2.5-1.25-4-.5Zm4 .5v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olqai6pvw {
  d: path("M4.5 7.5h15l-.75 12a2 2 0 0 1-2 2h-9.5a2 2 0 0 1-2-2Zm4.5 0V6a3 3 0 0 1 6 0v1.5");
}

</style>
