<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8e4sbcit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jet-ski-sharp" /></template>
<style>
.w8e4sbcit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13.25H8.5l.55-.83l.4-.59L10 11h5.5l.82.57l4.11 2.86l.82.57l-.63.77l-.99 1.21l-.63.77H4.25l-.32-.95l-.86-2.6l-.32-.95zM6 15.5h7.25M14.5 11L13 7.25h2.5m-12.75 14c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
