<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn6-1fbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-kid" /></template>
<style>
.zn6-1fbqa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.495 4.995Q4.25 6.24 4.25 8t1.245 3.005T8.5 12.25t3.005-1.245T12.75 8t-1.245-3.005T8.5 3.75T5.495 4.995M15.5 10.5q0-3.25 3.25-3.25T22 10.5t-3.25 3.25t-3.25-3.25M2.25 21q0-6.25 6.25-6.25T14.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 21q0-4.75-4.75-4.75T3.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T3 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21M19 15.25q-3.25 0-3.25 3.25T19 21.75t3.25-3.25T19 15.25");
}

</style>
