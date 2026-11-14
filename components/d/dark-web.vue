<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf8d46p5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dark-web" /></template>
<style>
.nf8d46p5j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75q-2.155 0-3.52 3.241q-1.116 2.651-1.219 6.259H5.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.75 12q0 3.003 2.123 5.127T12 19.25t5.127-2.123Q19.25 15.003 19.25 12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.761q-.103-3.608-1.219-6.259Q14.155 1.75 12 1.75q4.246 0 7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m13.489-.75q-.101-3.3-1.102-5.676Q13.159 3.25 12 3.25T9.863 5.574Q8.862 7.95 8.761 11.25z");
}

</style>
