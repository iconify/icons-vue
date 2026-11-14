<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yj5nmizkm"/><path class="zblzeub6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-proposer" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yj5nmizkm {
  d: path("m3 10l12.5-5v14L3 14Z");
}

.zblzeub6w {
  d: path("M7 15.5V20h3v-3.25M18.5 10L21 8.5M18.5 14l2.5 1.5");
}

</style>
