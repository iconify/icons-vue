<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ieku9mtxu"/><path class="fdg9awjcp"/><path class="lm96lcbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:expanding-file" /></template>
<style>
.fdg9awjcp {
  d: path("M4 13V8.5h6.5l1-1.5h3l1 1.5H20V13");
}

.ieku9mtxu {
  d: path("M3 21v-8h11l1-1.5h3.5l1 1.5H21v8Z");
}

.lm96lcbgz {
  d: path("M5 8.5V4h1.5l1-1.5h3l1 1.5H19v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
