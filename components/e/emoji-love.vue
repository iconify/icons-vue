<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="rkeuqsl7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emoji-love" /></template>
<style>
.rkeuqsl7p {
  d: path("M9 11.75s-2-1.25-2-2.5c0-.5.5-1 1-1s.75.25 1 .5c.25-.25.5-.5 1-.5s1 .5 1 1c0 1.25-2 2.5-2 2.5Zm6 0s-2-1.25-2-2.5c0-.5.5-1 1-1s.75.25 1 .5c.25-.25.5-.5 1-.5s1 .5 1 1c0 1.25-2 2.5-2 2.5ZM8.5 15c1 1.5 2.1 2.25 3.5 2.25s2.5-.75 3.5-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
