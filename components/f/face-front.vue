<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tikf0zxws"/><path class="yar0dm-me"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-front" /></template>
<style>
.tikf0zxws {
  d: path("M7.5 8a4.5 5.5 0 1 0 9 0a4.5 5.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yar0dm-me {
  d: path("M3 21.5c0-3.25 3-4.75 7-5.25V13m4 0v3.25c4 .5 7 2 7 5.25");
}

</style>
