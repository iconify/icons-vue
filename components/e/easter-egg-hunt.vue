<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dv9y59b4v"/><path class="damxvg8lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:easter-egg-hunt" /></template>
<style>
.damxvg8lo {
  d: path("m5.25 12l2.25-2l2.25 2L12 10l2.25 2l2.25-2l2.25 2M5.5 16.5l2-2l2.25 2l2.25-2l2.25 2l2.25-2l2 2");
}

.dv9y59b4v {
  d: path("M12 2.5c4.5 0 7 6.5 7 11.5c0 4.5-3 7.5-7 7.5s-7-3-7-7.5C5 9 7.5 2.5 12 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
