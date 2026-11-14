<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhq830yyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carton-stack" /></template>
<style>
.qhq830yyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 5.25h-5.5Q7 5.25 7 7.5v4q0 .75.25 1.25H5q-2.25 0-2.25 2.25v4q0 2.25 2.25 2.25h5.5q.951 0 1.5-.402q.549.402 1.5.402H19q2.25 0 2.25-2.25v-4q0-2.25-2.25-2.25h-2.25q.25-.5.25-1.25v-4q0-2.25-2.25-2.25M6 12.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 17.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 12.75");
}

</style>
