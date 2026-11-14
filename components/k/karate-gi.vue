<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr0k7ob4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:karate-gi" /></template>
<style>
.jr0k7ob4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L3 6l-.5 6.5H6v9h12v-9h3.5L21 6l-5.5-3m-7 0l4 11.5m3-11.5l-5 5.75M6 14.5h12m-5.5 0l-2 4m2-4l2 4");
}

</style>
