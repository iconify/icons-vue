<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hybkdg7nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ingot-stack" /></template>
<style>
.hybkdg7nr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.277 9.731l.909-2.5q.539-1.481 2.115-1.481h3.398q1.576 0 2.115 1.481l.909 2.5q.29.796.018 1.519h1.708q1.576 0 2.115 1.481l.909 2.5q.4 1.1-.272 2.06q-.672.959-1.843.959h-3.966q-1.171 0-1.843-.959q-.672-.96-.272-2.06l.902-2.481H9.821l.902 2.481q.4 1.1-.272 2.06q-.672.959-1.843.959H4.642q-1.171 0-1.843-.959q-.672-.96-.272-2.06v-.001l.909-2.499q.539-1.481 2.115-1.481h1.708q-.272-.723.018-1.519");
}

</style>
