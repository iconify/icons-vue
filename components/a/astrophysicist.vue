<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7t7xwl3s"/><path class="ac6p76bwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:astrophysicist" /></template>
<style>
.ac6p76bwm {
  d: path("M15.25 20.25a4 2-45 0 0 5.5-5.5a4 2-45 0 0-5.5 5.5Z");
}

.i7t7xwl3s {
  d: path("M12.372 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.682 0 1.339.058 1.96.169M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.75 7.75a4 2 45 0 0 5.5 5.5a4 2 45 0 0-5.5-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
