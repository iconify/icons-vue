<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-dt5-mus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eas-alarm" /></template>
<style>
.p-dt5-mus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 6h1.75A2.625 2.625 0 0 1 15.5 8.625v8.75A2.625 2.625 0 0 1 12.875 20h-1.75A2.625 2.625 0 0 1 8.5 17.375v-8.75A2.625 2.625 0 0 1 11.125 6M6.5 21.5h11M10 6V5a2 2 0 0 1 4 0v1M7.237 9.25a5.5 5.5 0 0 1 0-5.5m9.526 0a5.5 5.5 0 0 1 0 5.5m-12.467.842a8.5 8.5 0 0 1 0-7.184m15.408 0a8.5 8.5 0 0 1 0 7.184");
}

</style>
