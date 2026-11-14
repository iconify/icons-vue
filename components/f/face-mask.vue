<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo_5oh02n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-mask" /></template>
<style>
.zo_5oh02n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h14v9H5ZM5 9c-2 0-2.5 1.5-2.5 3S3 15 5 15m14-6c2 0 2.5 1.5 2.5 3s-.5 3-2.5 3M8 10.5h8m-8 3h8");
}

</style>
