<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="ar_krlbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folder-shared" /></template>
<style>
.ar_krlbzy {
  d: path("M8.5 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M7 16.25C7 14.9 8.3 14 10 14s3 .9 3 2.25m.75-4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M15 14c1.25 0 2 .75 2 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3wixnhae {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
