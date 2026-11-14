<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yusw6cykf"/><path class="np188tb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carol-songbook" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.np188tb7r {
  d: path("M14.75 14.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3 0V8.5l1.25 1");
}

.yusw6cykf {
  d: path("M12 6c-2-2-6-2.5-9.5-2v15c3.5-.5 7.5 0 9.5 2m0-15c2-2 6-2.5 9.5-2v15c-3.5-.5-7.5 0-9.5 2m0-15v15");
}

</style>
