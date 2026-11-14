<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z76qhbb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:document-retention" /></template>
<style>
.z76qhbb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10V4a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1v6M3 10h18v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm6.5-3.5h5m-4.5 8h4");
}

</style>
