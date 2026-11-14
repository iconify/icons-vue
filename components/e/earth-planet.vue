<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="qt2t-736g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-planet" /></template>
<style>
.qt2t-736g {
  d: path("M3.75 7.25H7.5c2 0 3 1.75 2 3.75l-1 2c-.75 1.5-1.5 3-3 3.75H3.75m13-13C15 5.5 14 7.5 15 9.5s-1.5 3.5-.5 5.5c.75 1.5 3.5.5 6.75-.5");
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
