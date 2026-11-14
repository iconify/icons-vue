<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyrlk0i8z"/><path class="yd9010b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cover-level-premium" /></template>
<style>
.fyrlk0i8z {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yd9010b7q {
  d: path("M8.5 14.25L7 21l2.75-1.25L12 21l2.25-1.25L17 21l-1.5-6.75m-3.03-7.272l.12.249a1.5 1.5 0 0 0 1.151.837l.275.037a.522.522 0 0 1 .29.894l-.2.191a1.5 1.5 0 0 0-.44 1.354l.05.272a.522.522 0 0 1-.761.553l-.243-.132a1.5 1.5 0 0 0-1.424 0l-.243.132a.522.522 0 0 1-.761-.553l.05-.272a1.5 1.5 0 0 0-.44-1.354l-.2-.191a.522.522 0 0 1 .29-.894l.275-.037a1.5 1.5 0 0 0 1.151-.837l.12-.249a.522.522 0 0 1 .94 0");
}

</style>
