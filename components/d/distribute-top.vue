<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eepkf4b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:distribute-top" /></template>
<style>
.eepkf4b7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 2.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 2.926 1.75 3t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M7.75 8v11q0 3-3 3t-3-3V8q0-1.243.879-2.121Q3.507 5 4.75 5q3 0 3 3M15 11.5V8q0-3-3-3T9 8v3.5q0 3 3 3t3-3M22.25 8v7.5q0 3-3 3t-3-3V8q0-3 3-3t3 3");
}

</style>
