<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgi0zvbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-compact" /></template>
<style>
.wgi0zvbry {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 4.75v1.5h-6.5q-2.485 0-4.243 1.757Q1.75 9.765 1.75 12.25v.5q0 2.485 1.757 4.243Q5.265 18.75 7.75 18.75h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-.5q0-2.485-1.757-4.243q-.389-.388-.813-.691q.07-.15.07-.316V4.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 4h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146m4 1.824q-.933-.324-2-.324h-.5V5.5h2.5zM8.5 12.5Q8.5 9 12 9t3.5 3.5T12 16t-3.5-3.5");
}

</style>
