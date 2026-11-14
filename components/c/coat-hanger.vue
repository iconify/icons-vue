<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmxpg96w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coat-hanger" /></template>
<style>
.lgmxpg96w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 6.5q0-2.75 2.75-2.75t2.75 2.75q0 2.345-2 2.69v1.448l8.216 6.525l.02.016q.857.73.548 1.813t-1.423 1.25q-.055.008-.111.008H4q-.056 0-.111-.008q-1.114-.168-1.423-1.25t.548-1.813l.02-.016l8.216-6.525V8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 7.75q1.25 0 1.25-1.25T12 5.25T10.75 6.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T10 7.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 6.5M3.979 18.327q-.114.103-.071.253q.039.135.164.17h15.856q.125-.035.164-.17q.043-.15-.071-.253L12 11.958z");
}

</style>
