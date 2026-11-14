<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3niz9b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dandruff" /></template>
<style>
.h3niz9b9z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 4.641Q7.25 6.032 7.25 8t1.391 3.359T12 12.75t3.359-1.391T16.75 8t-1.391-3.359T12 3.25T8.641 4.641m12.014-.796q1.155 1.155 0 2.31t-2.31 0t0-2.31t2.31 0m-.5 10.31q1.155-1.155 0-2.31t-2.31 0t0 2.31t2.31 0m-14-2.31q1.155 1.155 0 2.31t-2.31 0t0-2.31t2.31 0M2.75 21q0-3.143 2.8-5.028Q8.106 14.25 12 14.25t6.45 1.722q2.8 1.885 2.8 5.028q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 21");
}

</style>
