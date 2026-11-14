<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t55ktwuck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:linear-graph" /></template>
<style>
.t55ktwuck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 19.75V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q3.574 2.25 3.5 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 2.926 2.75 3v17.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 19.75zM15.5 6q0-2.5 2.5-2.5q1.036 0 1.768.732T20.5 6t-.732 1.768T18 8.5q-.72 0-1.232-.207l-6.475 6.475q.207.512.207 1.232q0 2.5-2.5 2.5T5.5 16T8 13.5q.72 0 1.232.207l6.475-6.475Q15.5 6.72 15.5 6");
}

</style>
