<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5z2gqbug"/><path class="r20jktb2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guest-feedback" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5z2gqbug {
  d: path("M4.5 3.5h15a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H10l-4.5 3.5V17h-1a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2");
}

.r20jktb2j {
  d: path("m12.5 7.5l.159.396a1.5 1.5 0 0 0 1.257.937l.511.047a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.106.583a.574.574 0 0 1-.883.58l-.293-.195a1.5 1.5 0 0 0-1.664 0l-.293.195a.574.574 0 0 1-.883-.58l.106-.583a1.5 1.5 0 0 0-.488-1.397l-.36-.315a.569.569 0 0 1 .323-.995l.511-.047a1.5 1.5 0 0 0 1.257-.937L11.5 7.5a.539.539 0 0 1 1 0");
}

</style>
