<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zd5ma_biy"/><path class="j3prsdbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beach-waves" /></template>
<style>
.j3prsdbnq {
  d: path("M7.5 17.5c1.25-3 3-5 5-5.75M2.5 21h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd5ma_biy {
  d: path("M2.5 17.5C4.5 10 9 5 15 5c3.75 0 6.5 2.5 6.5 5.5c0 2.5-2.5 3.75-4.5 2.5c-1.5-1-1.5-3 0-4");
}

</style>
