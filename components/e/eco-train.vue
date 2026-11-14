<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jy4wwripe"/><path class="tg5a8yg9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-train" /></template>
<style>
.jy4wwripe {
  d: path("M13.728 17.5H5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T4 16.5v-13q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T5 2.5h9q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T15 3.5v11.786");
}

.tg5a8yg9t {
  d: path("M7 5.5h5v4H7Zm.5 8h.01m3.99 0h.01m-4.01 4L6 21m5.5-3.5L13 21m3 .25c0-3.75 2-5.75 5.75-5.75c0 3.75-2 5.75-5.75 5.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
