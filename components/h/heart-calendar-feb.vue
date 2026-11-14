<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cel3a8n-d"/><path class="ojyywmb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-calendar-feb" /></template>
<style>
.cel3a8n-d {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.25A4.375 4.375 0 0 1 7.375 4.5M8 2.5v4m8-4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojyywmb9z {
  fill: currentColor;
  d: path("M12 17c-3-2-3.5-3.5-3.5-4.75c0-1.5 2-2.25 3.5-.75c1.5-1.5 3.5-.75 3.5.75C15.5 13.5 15 15 12 17");
}

</style>
