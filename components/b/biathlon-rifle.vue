<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itv1cabnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biathlon-rifle" /></template>
<style>
.itv1cabnd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 5.25h4.75q2.125 0 2.125 2.125T13.625 9.5h-4.75Q6.75 9.5 6.75 7.375T8.875 5.25m6.375 7h6.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H5q.125 0 .243-.041q.119-.04.217-.117l4.297-3.342H14.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146zm-1.5 0v1.5H9.5q-.125 0-.243.041q-.119.04-.217.117L4.743 17.25H3.25v-5z");
}

</style>
