<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7xcg-tow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-suite" /></template>
<style>
.g7xcg-tow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 20.75V4q0-2.25 2.25-2.25h9q2.25 0 2.25 2.25v16.75h2.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm1.5 0h10.5V4q0-.75-.75-.75h-9q-.75 0-.75.75zm6.5-10h1.5Q17 10.75 17 13v5q0 2.25-2.25 2.25h-1.5Q11 20.25 11 18v-5q0-2.25 2.25-2.25");
}

</style>
