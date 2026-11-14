<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrvum9pgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canoe-paddle" /></template>
<style>
.hrvum9pgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.718 5.282l-7.425 7.425m-1.768-1.768l3.536 3.536l-6.011 6.01l-3.535-3.535Zm7.778-7.071l2.829 2.829");
}

</style>
