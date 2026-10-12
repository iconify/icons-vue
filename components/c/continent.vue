<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpx78nlzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:continent" /></template>
<style>
.cpx78nlzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.25C6.63 3.54 8.79 3.08 10 3s2.08.25 2.75.75S13.38 5.25 14 6c.63.75 2.29 1.46 2.5 2.25s-.79 1.63-1.25 2.5c-.46.88-1.17 1.71-1.5 2.75s-.08 2.29-.5 3.5s-1.37 3.54-2 3.75c-.62.21-1.37-1.42-1.75-2.5c-.37-1.08-.17-2.87-.5-4c-.33-1.12-.71-2.12-1.5-2.75c-.79-.62-2.54-.29-3.25-1s-1.21-2.21-1-3.25s1.13-2.29 2.25-3M17.25 14.5c.67-.67 1.33-.67 2 0s1.33.67 2 0m-4 3.5c.67-.67 1.33-.67 2 0s1.33.67 2 0");
}

</style>
