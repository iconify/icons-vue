<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl1vh2bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-bivvy" /></template>
<style>
.pl1vh2bvf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.758 18.75Q2.9 12.519 5.427 8.478Q8.069 4.25 12 4.25t6.573 4.228q2.527 4.041 2.669 10.272H22q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T2 18.75zm6.501 0h5.482q-.148-6-2.741-6t-2.741 6m6.982 0q-.189-7.5-4.241-7.5t-4.241 7.5h-3.5q.138-5.795 2.439-9.478Q8.9 5.75 12 5.75t5.302 3.522q2.301 3.683 2.439 9.478z");
}

</style>
