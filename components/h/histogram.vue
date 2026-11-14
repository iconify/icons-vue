<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e08l0zb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:histogram" /></template>
<style>
.e08l0zb2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 3v16.75h1.076q-.076-.337-.076-.75v-3.5q0-2.25 2.25-2.25q.413 0 .75.076V10.5q0-2.25 2.25-2.25q.413 0 .75.076V7q0-2.25 2.25-2.25T15.75 7v4.326q.337-.076.75-.076q2.25 0 2.25 2.25V19q0 .413-.076.75H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T4.25 3");
}

</style>
