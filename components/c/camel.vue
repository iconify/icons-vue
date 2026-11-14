<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz8k7ccgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camel" /></template>
<style>
.bz8k7ccgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13.5c-.5-3.5 1-7 3.5-7C8.75 6.5 9 9 9.75 9s1-2.5 2.75-2.5s2 3.5 3 3.5L17 4h3l1.5 2l-2 .75c.25 2.75 0 6.75-1.5 6.75Zm1.5 0v6m3-6v6m6-6v6m3-6v6m-14.5 0h19");
}

</style>
