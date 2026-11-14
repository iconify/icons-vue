<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-t3p0kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:device-search" /></template>
<style>
.xl-t3p0kj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 2.25h-5.5q-2.485 0-4.243 1.757Q1.75 5.765 1.75 8.25v5.5q0 2.485 1.757 4.243Q5.265 19.75 7.75 19.75h5.5q.314 0 .616-.028q-.616-.983-.616-2.222q0-1.76 1.245-3.005T17.5 13.25q.95 0 1.75.363V8.25q0-2.485-1.757-4.243Q15.735 2.25 13.25 2.25M6 10q0-3.5 3.5-3.5T13 10t-3.5 3.5T6 10m11.5 4.5q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5m-.25-1.5q0-.25.25-.25t.25.25t-.25.25t-.25-.25");
}

</style>
