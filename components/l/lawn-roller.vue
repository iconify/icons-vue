<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bynx6ybuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lawn-roller" /></template>
<style>
.bynx6ybuc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.976 10.89q2.274.719 2.274 5.11q0 5.25-3.25 5.25H6.5q-1.477 0-2.423-1.704Q3.25 18.058 3.25 16q0-5.25 3.25-5.25h7.949l2.031-6.5H16q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T20 4.25h-1.949zM6.5 12.25h5.954q-.704 1.306-.704 3.75t.704 3.75H6.5q-.594 0-1.112-.932Q4.75 17.67 4.75 16q0-3.75 1.75-3.75");
}

</style>
