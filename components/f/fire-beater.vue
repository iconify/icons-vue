<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibbinhbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-beater" /></template>
<style>
.ibbinhbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.003 5.053l1.944 1.944a2.625 2.625 0 0 1 0 3.713l-1.237 1.237a2.625 2.625 0 0 1-3.713 0l-1.944-1.944a2.625 2.625 0 0 1 0-3.713l1.237-1.237a2.625 2.625 0 0 1 3.713 0m-3.978 5.922l-8.839 8.839M17.975 6.025l-4.95 4.95m-.353-5.303l5.656 5.656m-.078 4.922C18.75 17.5 21 18 21 19a2.75 2.75 0 0 1-5.5 0c0-1 .75-1.75 1.75-2.25Z");
}

</style>
