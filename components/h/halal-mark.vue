<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-hxnseev"/><path class="sinyhybqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:halal-mark" /></template>
<style>
.b-hxnseev {
  d: path("m12.64 3.14l.85.51q.65.38 1.4.37l.99-.02q.75-.01 1.11.64l.48.87q.36.66 1.02 1.02l.87.48q.65.37.64 1.11l-.02.99q-.01.75.37 1.4l.51.85q.39.64 0 1.28l-.51.85q-.38.65-.37 1.4l.02.99q.01.75-.64 1.11l-.87.48q-.66.36-1.02 1.02l-.48.87q-.36.65-1.11.64l-.99-.02q-.75-.01-1.4.37l-.85.51q-.64.39-1.28 0l-.85-.51q-.65-.38-1.4-.37l-.99.02q-.74.01-1.11-.64l-.48-.87q-.36-.66-1.02-1.02l-.87-.48q-.65-.36-.64-1.11l.02-.99q.01-.75-.37-1.4l-.51-.85q-.39-.64 0-1.28l.51-.85q.38-.65.37-1.4L4 8.12q-.01-.75.64-1.11l.87-.48q.66-.36 1.02-1.02l.48-.87q.36-.65 1.11-.64l.99.02q.75.01 1.4-.37l.85-.51q.64-.39 1.28 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sinyhybqv {
  d: path("M14.5 8.25a4.5 4.5 0 1 0 0 7.5a4 4 0 0 1 0-7.5");
}

</style>
