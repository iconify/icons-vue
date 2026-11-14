<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="treyn1bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:asterism" /></template>
<style>
.treyn1bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.625 4.5l.24.577A1.5 1.5 0 0 0 14.25 6h.5a.57.57 0 0 1 .379.997l-.464.412a1.5 1.5 0 0 0-.465 1.458l.184.795a.667.667 0 0 1-1.009.713l-.57-.363a1.5 1.5 0 0 0-1.61 0l-.57.363a.667.667 0 0 1-1.009-.713l.184-.795a1.5 1.5 0 0 0-.465-1.458l-.464-.412A.57.57 0 0 1 9.25 6h.5a1.5 1.5 0 0 0 1.385-.923l.24-.577a.677.677 0 0 1 1.25 0M7 14.75l.159.396a1.5 1.5 0 0 0 1.257.937l.511.047a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.106.583a.574.574 0 0 1-.883.58l-.293-.195a1.5 1.5 0 0 0-1.664 0L5.375 20a.574.574 0 0 1-.883-.58l.106-.583a1.5 1.5 0 0 0-.488-1.397l-.36-.315a.569.569 0 0 1 .323-.995l.511-.047a1.5 1.5 0 0 0 1.257-.937L6 14.75a.539.539 0 0 1 1 0m11 0l.159.396a1.5 1.5 0 0 0 1.257.937l.511.047a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.106.583a.574.574 0 0 1-.883.58l-.293-.195a1.5 1.5 0 0 0-1.664 0l-.293.195a.574.574 0 0 1-.883-.58l.106-.583a1.5 1.5 0 0 0-.488-1.397l-.36-.315a.569.569 0 0 1 .323-.995l.511-.047a1.5 1.5 0 0 0 1.257-.937L17 14.75a.539.539 0 0 1 1 0");
}

</style>
