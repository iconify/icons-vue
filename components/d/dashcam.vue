<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4g3x9b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dashcam" /></template>
<style>
.a4g3x9b-k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 3.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 3.926 2.25 4t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 4.75h8.25v2H8q-1.76 0-3.005 1.245T3.75 11v5q0 1.76 1.245 3.005T8 20.25h8q1.76 0 3.005-1.245T20.25 16v-5q0-1.76-1.245-3.005T16 6.75h-3.25v-2H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.75 4t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 3.25M8 13.5q0-4 4-4q1.657 0 2.828 1.172Q16 11.843 16 13.5q0 4-4 4t-4-4");
}

</style>
