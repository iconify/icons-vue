<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7y2ydyvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agave" /></template>
<style>
.q7y2ydyvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5c-1.25-6-1.25-12 0-17.5c1.25 5.5 1.25 11.5 0 17.5m0 0C9.5 16 7 10.5 6 5m6 15.5c2.5-4.5 5-10 6-15.5m-6 15.5Q6.75 18.25 3 13m9 7.5q5.25-2.25 9-7.5");
}

</style>
