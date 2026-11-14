<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i27nykbpw"/><path class="ul-3xbg2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badminton-racket-shuttle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i27nykbpw {
  d: path("M8 8a4 5.25 0 1 0 8 0a4 5.25 0 1 0-8 0m.25 3.75L3 17m14.948-2.448l1.037 1.97a1.5 1.5 0 0 1-.266 1.759l-.438.438a1.5 1.5 0 0 1-1.759.266l-1.97-1.037a1.5 1.5 0 0 1-.362-2.388l1.37-1.37a1.5 1.5 0 0 1 2.388.362");
}

.ul-3xbg2r {
  d: path("M18 19.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
