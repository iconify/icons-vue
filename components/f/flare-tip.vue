<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kizbsibzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flare-tip" /></template>
<style>
.kizbsibzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 21.5l1-9.25m3 9.25l-1-9.25M5 21.5h14m-7-19c2 2.5 4 4.25 4 6a4 4 0 0 1-8 0c0-1.75 2-3.5 4-6");
}

</style>
