<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ivqzvlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capping-machine" /></template>
<style>
.t4ivqzvlr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q3.25 0 3.25 3.25T15.5 8.25h-.576Q15 8.587 15 9q0 .789-.277 1.301q.027.098.027.199v.81q2 .345 2 2.69v7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V14q0-2.345 2-2.69v-.81q0-.101.027-.199Q9 9.789 9 9q0-.413.076-.75H8.5Q5.25 8.25 5.25 5T8.5 1.75");
}

</style>
