<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikhz-ac-p"/><path class="ipu56dpge"/><path class="a2-5zzbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-pressure-reading" /></template>
<style>
.a2-5zzbpt {
  d: path("M12 16.5v3m-4 1h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ikhz-ac-p {
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v4.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.75A4.375 4.375 0 0 1 6.875 3M5.5 7h6m-4 5.5h4m2.75-7l-2 8.5");
}

.ipu56dpge {
  fill: currentColor;
  d: path("M17 13s-2.25-1.5-2.25-3.25c0-.75.6-1.25 1.25-1.25c.4 0 .75.25 1 .5c.25-.25.6-.5 1-.5c.65 0 1.25.5 1.25 1.25C19.25 11.5 17 13 17 13");
}

</style>
