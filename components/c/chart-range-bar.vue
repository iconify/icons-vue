<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioih93byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-range-bar" /></template>
<style>
.ioih93byn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 1.75q2.25 0 2.25 2.25v5q0 2.25-2.25 2.25T17.25 9V4q0-2.25 2.25-2.25m-10 1q2.25 0 2.25 2.25v6.5q0 2.25-2.25 2.25T7.25 11.5V5q0-2.25 2.25-2.25M16.75 9q0-2.25-2.25-2.25T12.25 9v7.5q0 2.25 2.25 2.25t2.25-2.25zm-10 1.5q0-2.25-2.25-2.25q-.932 0-1.591.659T2.25 10.5V15q0 2.25 2.25 2.25T6.75 15zM2.5 20.75h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
