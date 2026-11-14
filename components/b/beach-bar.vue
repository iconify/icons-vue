<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1igb4beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beach-bar" /></template>
<style>
.z1igb4beo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 6.5l4-4h10l4 4L18.75 8L16.5 6.5L14.25 8L12 6.5L9.75 8L7.5 6.5L5.25 8ZM5.25 8v7m13.5-7v7m-14 0h14.5A1.75 1.75 0 0 1 21 16.75v2.5A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-2.5A1.75 1.75 0 0 1 4.75 15m4.75-4h5L12 13.75Zm2.5 2.75V15");
}

</style>
