<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m5p2tvb5y"/><path class="md0xiobel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-first-win" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5p2tvb5y {
  d: path("m12.776 2.602l.279.216a1.5 1.5 0 0 0 1.123.301l.348-.048a1.27 1.27 0 0 1 1.345.777l.133.326a1.5 1.5 0 0 0 .822.822l.326.133a1.27 1.27 0 0 1 .777 1.345l-.048.348a1.5 1.5 0 0 0 .301 1.123l.216.279a1.27 1.27 0 0 1 0 1.552l-.216.279a1.5 1.5 0 0 0-.301 1.123l.048.348a1.27 1.27 0 0 1-.777 1.345l-.326.133a1.5 1.5 0 0 0-.822.822l-.133.326a1.27 1.27 0 0 1-1.345.777l-.348-.048a1.5 1.5 0 0 0-1.123.301l-.279.216a1.27 1.27 0 0 1-1.552 0l-.279-.216a1.5 1.5 0 0 0-1.123-.301l-.348.048a1.27 1.27 0 0 1-1.345-.777l-.133-.326a1.5 1.5 0 0 0-.822-.822l-.326-.133a1.27 1.27 0 0 1-.777-1.345l.048-.348a1.5 1.5 0 0 0-.301-1.123l-.216-.279a1.27 1.27 0 0 1 0-1.552l.216-.279a1.5 1.5 0 0 0 .301-1.123l-.048-.348a1.27 1.27 0 0 1 .777-1.345l.326-.133a1.5 1.5 0 0 0 .822-.822l.133-.326a1.27 1.27 0 0 1 1.345-.777l.348.048a1.5 1.5 0 0 0 1.123-.301l.279-.216a1.27 1.27 0 0 1 1.552 0");
}

.md0xiobel {
  d: path("M8.5 14L7 21l5-2.5l5 2.5l-1.5-7M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
