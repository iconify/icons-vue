<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrq-gsbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boxing-workout" /></template>
<style>
.zrq-gsbbr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.636 6.078Q4.922 8.281 5.25 11.045V16q0 2.167 1.252 3.082q-.252.458-.252 1.168q0 2 2 2h7q2 0 2-2q0-1.515-1.147-1.882q.346-.271.67-.595Q18.75 15.796 18.75 13V9.5q0-.047-.006-.093q-.35-2.793-2.572-4.521t-5.015-1.378t-4.521 2.57M5.25 12q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 11.25h3.5q2.75 0 2.75 2.75T9.5 16.75H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 16q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 15.25h2.5q1.25 0 1.25-1.25T9.5 12.75H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 12");
}

</style>
