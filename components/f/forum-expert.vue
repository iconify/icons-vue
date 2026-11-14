<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p66dwqbqx"/><path class="zbe3v3b1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forum-expert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p66dwqbqx {
  d: path("M12 3.5c5 0 8.5 3.25 8.5 7.5S17 18.5 12 18.5c-1.25 0-2.5-.25-3.5-.5l-5 2L5 15.75c-1-1.25-1.5-3-1.5-4.75C3.5 6.75 7 3.5 12 3.5");
}

.zbe3v3b1z {
  d: path("m12.558 8.231l.207.456a1.5 1.5 0 0 0 1.199.871l.497.055a.613.613 0 0 1 .345 1.063l-.369.336a1.5 1.5 0 0 0-.458 1.41l.1.49a.613.613 0 0 1-.903.656l-.435-.247a1.5 1.5 0 0 0-1.482 0l-.435.247a.613.613 0 0 1-.903-.656l.1-.49a1.5 1.5 0 0 0-.458-1.41l-.369-.336a.613.613 0 0 1 .345-1.063l.497-.055a1.5 1.5 0 0 0 1.199-.871l.207-.456a.613.613 0 0 1 1.116 0");
}

</style>
