<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc5ii4y-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lane-arrow-left-u-turn" /></template>
<style>
.gc5ii4y-n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 8.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8.5q0-2.071-1.464-3.536Q15.821 3.5 13.75 3.5t-3.536 1.464T8.75 8.5v5.189L6.53 11.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T6 11.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T5.25 12t.057.287t.163.243l3.5 3.5q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16l.003-.004l3.5-3.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T13 11.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-2.22 2.219V8.5q0-3.5 3.5-3.5t3.5 3.5");
}

</style>
