<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd9721ahr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clinch" /></template>
<style>
.qd9721ahr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.848 5.348Q3.75 6.447 3.75 8q0 3.75 3.75 3.75T11.25 8T7.5 4.25q-1.553 0-2.652 1.098M12.75 8q0-3.75 3.75-3.75T20.25 8t-3.75 3.75T12.75 8m-11 12.5V18q0-4.75 5.75-4.75q2.767 0 4.5 1.643q1.733-1.643 4.5-1.643q5.75 0 5.75 4.75v2.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
