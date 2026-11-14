<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rerxnwb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cleanser-bottle" /></template>
<style>
.rerxnwb-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 21.5H4v-12h12.5v3m-6.25-3V4h5.25v1.5M8 6.5h4.5m6 8c1.25 1.75 2.75 3.25 2.75 4.5a2.75 2.75 0 0 1-5.5 0c0-1.25 1.5-2.75 2.75-4.5Z");
}

</style>
