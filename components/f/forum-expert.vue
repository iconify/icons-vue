<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kh8je4brm"/><path class="p6xaalb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forum-expert" /></template>
<style>
.kh8je4brm {
  d: path("M12 3.5c5 0 8.5 3.25 8.5 7.5S17 18.5 12 18.5c-1.25 0-2.5-.25-3.5-.5l-5 2L5 15.75c-1-1.25-1.5-3-1.5-4.75C3.5 6.75 7 3.5 12 3.5Z");
}

.p6xaalb3e {
  d: path("m12 7l1.117 2.463l2.687.301l-1.997 1.823l.544 2.649L12 12.9l-2.351 1.336l.544-2.649l-1.997-1.823l2.687-.301Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
