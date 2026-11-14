<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xphg22b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:l-cut" /></template>
<style>
.xphg22b0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 4.75h3.375q3.375 0 3.375 3.375v.25q0 1.398-.989 2.386q-.988.989-2.386.989H8.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T9.25 11V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T8.5 4.75m0 0q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V11q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014H5.125q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-.25q0-3.375 3.375-3.375zM18.875 13H5.125q-1.398 0-2.386.989q-.989.988-.989 2.386v.25Q1.75 20 5.125 20h13.75q3.375 0 3.375-3.375v-.25Q22.25 13 18.875 13");
}

</style>
