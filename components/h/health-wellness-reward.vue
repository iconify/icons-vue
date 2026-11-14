<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6grmfbsj"/><path class="rnl6cdssz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-wellness-reward" /></template>
<style>
.rnl6cdssz {
  d: path("m8.5 10l-2-7.5h4L12 7m3.5 3l2-7.5h-4L12 7m0 10s-2.75-1.75-2.75-3.5c0-1 .75-1.5 1.5-1.5c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c.75 0 1.5.5 1.5 1.5C14.75 15.25 12 17 12 17Z");
}

.s6grmfbsj {
  d: path("M6.5 14a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
