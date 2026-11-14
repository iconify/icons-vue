<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvlc74b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:letterpress" /></template>
<style>
.yvlc74b6j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T19.75 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25M8.022 12.75l3.298-7.067q.063-.135.173-.236t.251-.152t.289-.044q.149.006.284.069q.12.056.213.15q.094.093.15.213l3.298 7.067h.397q3.375 0 3.375 3.375v2.25q0 3.375-3.375 3.375h-8.75q-3.375 0-3.375-3.375v-2.25q0-3.375 3.375-3.375zm4.9-3L12 7.774l-.922 1.976zm.7 1.5h-3.244l-.7 1.5h4.644z");
}

</style>
