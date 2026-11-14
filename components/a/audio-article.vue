<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3jfcfblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audio-article" /></template>
<style>
.n3jfcfblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 4.5h9.75A2.625 2.625 0 0 1 19.5 7.125v5.25A2.625 2.625 0 0 1 16.875 15h-9.75A2.625 2.625 0 0 1 4.5 12.375v-5.25A2.625 2.625 0 0 1 7.125 4.5M2.5 18.5h19M9 8.5V11m3-3.75v5m3-3.75V11");
}

</style>
