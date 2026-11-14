<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihkws6bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bed-cleaning" /></template>
<style>
.ihkws6bvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5V20m0-7.5h16a2 2 0 0 1 2 2V20M3 16.5h18m-5.5-14l1.237 2.263L19 6l-2.263 1.237L15.5 9.5l-1.237-2.263L12 6l2.263-1.237Z");
}

</style>
