<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rle5dt74u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capture-card" /></template>
<style>
.rle5dt74u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 5.75H3.5V19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2 19V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H7q.152 0 .292.059q.387-.059.833-.059h10.75q3.375 0 3.375 3.375v5.75q0 3.182-3 3.364V18.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.75h-.625q-3.375 0-3.375-3.375v-5.75q0-1.125.375-1.875M13.5 7Q10 7 10 10.5t3.5 3.5t3.5-3.5T13.5 7m4.25 10.75v-1h-7.5v1z");
}

</style>
