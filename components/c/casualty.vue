<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-663cbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:casualty" /></template>
<style>
.g-663cbep {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.5q0-3.25 3.25-3.25t3.25 3.25T5 13.75T1.75 10.5M19.5 8.25h-7.25Q9.5 8.25 9.5 11t2.75 2.75h7.25q2.75 0 2.75-2.75T19.5 8.25M2.5 15h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T2.5 15");
}

</style>
