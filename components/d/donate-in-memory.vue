<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apk3gupag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-in-memory" /></template>
<style>
.apk3gupag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 10h2.5A1.75 1.75 0 0 1 15 11.75v7.5A1.75 1.75 0 0 1 13.25 21h-2.5A1.75 1.75 0 0 1 9 19.25v-7.5A1.75 1.75 0 0 1 10.75 10M5.5 21h13M12 8.25c-1.25 0-2-.75-2-2s1-2.25 2-3.5C13 4 14 5 14 6.25s-.75 2-2 2m0 0V10");
}

</style>
