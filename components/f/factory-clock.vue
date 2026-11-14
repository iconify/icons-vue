<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnd-48bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:factory-clock" /></template>
<style>
.mnd-48bbx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 19.5V8q0-.098.025-.193t.075-.181q.049-.085.118-.155t.154-.119l6-3.5q.129-.075.277-.095t.292.018t.263.128t.194.219q.102.175.102.378v2.194l4.872-2.842q.129-.075.277-.095t.292.018t.263.128t.194.219q.102.175.102.378v2.194l4.872-2.842q.064-.037.134-.061t.143-.034t.147-.006t.145.024q.071.018.138.051q.066.032.125.077t.108.1t.086.119q.102.175.102.378v15q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m6.391-9.359Q7.25 11.532 7.25 13.5t1.391 3.359T12 18.25t3.359-1.391T16.75 13.5t-1.391-3.359T12 8.75t-3.359 1.391");
}

</style>
