<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="im_1lxb4u"/><path class="ca2tu2bow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backhoe-loader" /></template>
<style>
.ca2tu2bow {
  d: path("M6.25 17.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4.25-5.25l2-2h2V6l-3 1.5m-12 3l-2-6l-2 6.5l1 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.im_1lxb4u {
  d: path("M6.5 15.5v-5H9V5h5v5.5h3.5v5Z");
}

</style>
