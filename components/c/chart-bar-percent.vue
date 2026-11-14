<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2b8s0i8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-bar-percent" /></template>
<style>
.y2b8s0i8d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2.25H5q-2.5 0-2.5 2.5V10q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T8 10V4.75q0-1.036-.732-1.768T5.5 2.25m6.25 0h.5q2.5 0 2.5 2.5V14q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 13.25h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.25 14V4.75q0-2.5 2.5-2.5m7.25 0h-.5q-2.5 0-2.5 2.5V7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V4.75q0-2.5-2.5-2.5");
}

</style>
