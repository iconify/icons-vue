<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg0l75bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:iron-high" /></template>
<style>
.hg0l75bmf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.25 10.75H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 18q0-.047.006-.093q.41-3.281 3.044-5.257q1.966-1.474 4.613-1.805l1.369-4.561q.017-.057.043-.111t.061-.103t.076-.093t.09-.079t.102-.063t.11-.047t.117-.028q.059-.01.119-.01h7.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-8.742 0h7.242v-3.5h-6.192zM9.25 15q0 1.5 1.5 1.5t1.5-1.5t-1.5-1.5t-1.5 1.5m5.25-1.5Q13 13.5 13 15t1.5 1.5T16 15t-1.5-1.5m2.25 1.5q0 1.5 1.5 1.5t1.5-1.5t-1.5-1.5t-1.5 1.5");
}

</style>
