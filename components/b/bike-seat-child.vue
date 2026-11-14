<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8eqsgbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-seat-child" /></template>
<style>
.l8eqsgbmu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.214 8.52l2.5 7.75q.036.112.036.23q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.294q-.228 1.903-1.64 3.316Q11.382 22.25 9 22.25t-4.066-1.684T3.25 16.5t1.684-4.066T9 10.75t4.066 1.684q1.412 1.413 1.64 3.316h3.264L15.954 9.5H4.25q-2 0-2-2V3.75q0-2 2-2H5q2 0 2 2V5h4q2 0 2 2v1h3.5q.163 0 .311.067l.031.015q.13.067.226.178q.095.11.142.249zM11.5 7q0-.5-.5-.5H6.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.5 5.75v-2q0-.5-.5-.5h-.75q-.5 0-.5.5V7.5q0 .5.5.5h7.25z");
}

</style>
