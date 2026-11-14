<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyf7hcctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:friend-remove" /></template>
<style>
.hyf7hcctq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 7.75Q3.5 4 7.25 4T11 7.75T7.25 11.5T3.5 7.75m13.25-3.5q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5t-3.5-3.5M3.355 16.06Q1.75 17.641 1.75 20q0 1.75 1.75 1.75H11q1.75 0 1.75-1.75q0-2.359-1.605-3.94Q9.563 14.5 7.25 14.5t-3.895 1.56M21 17.25h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 17.25");
}

</style>
