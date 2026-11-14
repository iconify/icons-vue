<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4phye79i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brooch-ancient" /></template>
<style>
.m4phye79i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.076 5.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 7.25h2.401Q3.25 9.679 3.25 13q0 3.624 2.563 6.187T12 21.75t6.187-2.563T20.75 13q0-3.321-2.151-5.75h.901q2.5 0 2.5-2.5t-2.5-2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T18.75 3t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1 0 1 1t-1 1h-2.576Q14.773 4.25 12 4.25t-4.924 1.5m1.919 4.245Q10.24 8.75 12 8.75t3.005 1.245T16.25 13t-1.245 3.005T12 17.25t-3.005-1.245T7.75 13t1.245-3.005");
}

</style>
