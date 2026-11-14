<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-gt7ndhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-form" /></template>
<style>
.g-gt7ndhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 21v-8.26L4.39 9.436q-.035-.048-.061-.101q-.617-1.233.328-2.178t2.178-.328q.148.074.251.202l.664.831V4.5q0-1.5 1.5-1.5l.055.001Q9.548 2 10.875 2q.962 0 1.354.525q.184-.025.396-.025q1.625 0 1.625 1.5v.502q.061-.002.125-.002Q16 4.5 16 6v8q0 1.562-.803 3.449q-.447 1.049-.447 1.551v2q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 21");
}

</style>
