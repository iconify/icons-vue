<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="gwlk2ticc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coin" /></template>
<style>
.gwlk2ticc {
  d: path("M14.75 9C14.5 8 13.4 7.5 12 7.5c-1.7 0-2.75.9-2.75 2c0 2.7 5.5 1.5 5.5 4.75c0 1.35-1.15 2.25-2.75 2.25c-1.5 0-2.5-.6-2.75-1.75M12 6v1.5m0 9V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
