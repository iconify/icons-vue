<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-7zrq1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-simple-sharp" /></template>
<style>
.qz-7zrq1z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.6141 11.0785L2 10.7782L12 2.9963L22 10.7782L22.3859 11.0785M4 9.2218L4 21L20 21L20 9.2218");
}

</style>
