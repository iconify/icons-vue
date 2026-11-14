<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z--h_cb4p"/><path class="pe3u3njpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garbage-patch" /></template>
<style>
.pe3u3njpu {
  d: path("m13.5 9l1.5 1l1.75-1.25l2.25 1M2.5 16.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-18 4q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z--h_cb4p {
  d: path("M5 12.75V8.5Q5 7 6.5 6.25V3.5h2v2.75Q10 7 10 8.5v4.25Zm8.5-7.25H19v7.25h-5.5Z");
}

</style>
