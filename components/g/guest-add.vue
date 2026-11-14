<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bipsssbyg"/><path class="s_2cqnbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-add" /></template>
<style>
.bipsssbyg {
  d: path("M5.75 7.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM3 21c0-4 3-6.25 7-6.25q1.82 0 3.15.491");
}

.s_2cqnbxn {
  d: path("M7.75 14.75L10 17.5l2.25-2.75M18 15v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
