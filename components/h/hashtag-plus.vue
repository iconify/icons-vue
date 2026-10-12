<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq5-t-pjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hashtag-plus" /></template>
<style>
.wq5-t-pjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 8.5l-1.5 12.25m6.5-12.25l-1.5 12.25M4 12.25h10.5M3.25 17h10.5m.75-7.5L17.75 6l1.75 1.75L21.25 6m-3.5-2.25h3v3");
}

</style>
