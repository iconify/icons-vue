<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_21zhbhq"/><path class="w4bpqm0yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:care-team" /></template>
<style>
.o_21zhbhq {
  d: path("M2.5 20.5c0-3 1.25-5 3-5s3 2 3 5Zm6.5 0C9 17 10.25 15 12 15s3 2 3 5.5Zm6.5 0c0-3 1.25-5 3-5s3 2 3 5ZM3.25 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm13 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.25 9a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm.25-.75h2.25m2.5 0h2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4bpqm0yt {
  d: path("M11 8.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
