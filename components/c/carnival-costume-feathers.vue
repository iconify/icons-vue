<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a68cwccto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carnival-costume-feathers" /></template>
<style>
.a68cwccto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17h16v3.5H4Zm8 0V3M9 17Q8.5 9 6.5 4M15 17q.5-8 2.5-13M6 17q-1-5-3.5-8.5M18 17q1-5 3.5-8.5");
}

</style>
