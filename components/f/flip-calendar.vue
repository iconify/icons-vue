<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7cyikm5o"/><path class="mkcw6bboq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flip-calendar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkcw6bboq {
  d: path("M20.5 15h-4a2 2 0 0 0-2 2v4M3.5 9.5h17M8 2.5v4m8-4v4");
}

.r7cyikm5o {
  d: path("M3.5 7A2.5 2.5 0 0 1 6 4.5h12A2.5 2.5 0 0 1 20.5 7v8l-6 6H6a2.5 2.5 0 0 1-2.5-2.5Z");
}

</style>
