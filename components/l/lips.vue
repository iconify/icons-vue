<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c1jr6db5e"/><path class="emjjmgbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lips" /></template>
<style>
.c1jr6db5e {
  d: path("M2.5 12Q7 6 10 6c1 0 1.5.75 2 .75S13 6 14 6q3 0 7.5 6c-3 4.5-6 6-9.5 6s-6.5-1.5-9.5-6");
}

.emjjmgbrt {
  d: path("M2.5 12c3.5-.5 6.5 1 9.5.25c3 .75 6-.75 9.5-.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
