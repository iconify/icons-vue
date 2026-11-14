<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs8i62b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-big-right-line" /></template>
<style>
.vs8i62b4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.983 14.077l-4.039 4.039q-.745.747-1.72.343t-.974-1.46q0-1.249-1.25-1.249h-1.812q-2.937 0-2.938-2.937v-1.625q0-2.938 2.938-2.938H12q1.25 0 1.25-1.25q-.001-1.055.974-1.459t1.721.343l4.038 4.039q2.077 2.077 0 4.154M4.25 15V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T3.5 8.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 8.926 2.75 9v6q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.25 15");
}

</style>
