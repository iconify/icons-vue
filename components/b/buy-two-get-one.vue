<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tph_wvbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buy-two-get-one" /></template>
<style>
.tph_wvbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 14h5.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 4.25 14m10 0h5.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 14.25 14m-5-7.5h5.5a1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 14.75 14h-5.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 9.25 6.5m2.75 0V14m0-7.5c0-3.25-3-4-3-2c0 1.25 2 2 3 2s3-.75 3-2c0-2-3-1.25-3 2");
}

</style>
