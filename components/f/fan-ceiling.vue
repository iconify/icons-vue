<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4r0jo1eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fan-ceiling" /></template>
<style>
.g4r0jo1eg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h1.75v7.277Q10.209 9.5 7 9.5q-4.75 0-4.75 2.25T7 14q.994 0 1.78-.099q-.03.284-.03.599t.03.599Q7.994 15 7 15q-4.75 0-4.75 2.25T7 19.5q4.199 0 4.686-1.758q.153.008.314.008t.314-.008Q12.801 19.5 17 19.5q4.75 0 4.75-2.25T17 15q-.994 0-1.78.099q.03-.284.03-.599t-.03-.599Q16.006 14 17 14q4.75 0 4.75-2.25T17 9.5q-3.209 0-4.25 1.027V3.25h1.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014");
}

</style>
