<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omq98ebct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lower-third-news" /></template>
<style>
.omq98ebct {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v7q0 1.76 1.245 3.005T6 18.25h5.25v1.5H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 19.75h-3.25v-1.5H18q1.76 0 3.005-1.245T22.25 14V7q0-1.76-1.245-3.005T18 2.75m-10.75 7h6.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-6.5q-2.5 0-2.5-2.5t2.5-2.5");
}

</style>
