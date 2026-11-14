<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubrt5gb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lens-adapter" /></template>
<style>
.ubrt5gb0s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 2.25Q2.25 2.25 2.25 4v16q0 1.75 1.75 1.75h1.5q1.75 0 1.75-1.75v-2.75h9.5v.25q0 1.75 1.75 1.75H20q1.75 0 1.75-1.75v-11q0-1.75-1.75-1.75h-1.5q-1.75 0-1.75 1.75v.25h-9.5V4q0-1.75-1.75-1.75zm8 4.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v9q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-9q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 6.75");
}

</style>
