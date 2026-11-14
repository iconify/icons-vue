<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z96kkobky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:holiday-hours-sign" /></template>
<style>
.z96kkobky {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 2.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 2.926 2.25 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h3.25v2.506q-1.6.083-2.755 1.239Q2.25 8.74 2.25 10.5V18q0 1.76 1.245 3.005T6.5 22.25h11q1.76 0 3.005-1.245T21.75 18v-7.5q0-1.76-1.245-3.005q-1.155-1.156-2.755-1.239V3.75H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.75 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 2.25m-13.25 4v-2.5h8.5v2.5zm.714 4.464Q9.929 9.25 12 9.25t3.536 1.464T17 14.25t-1.464 3.536Q14.071 19.25 12 19.25t-3.536-1.464Q7 16.321 7 14.25t1.464-3.536");
}

</style>
