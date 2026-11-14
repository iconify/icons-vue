<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqtuvwbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-noticeboard" /></template>
<style>
.kqtuvwbgj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 2.25h-13q-1.76 0-3.005 1.245T1.25 6.5v6q0 1.76 1.245 3.005q1.155 1.156 2.755 1.239V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.75h10.5v4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.756q1.6-.083 2.755-1.239Q22.75 14.26 22.75 12.5v-6q0-1.76-1.245-3.005T18.5 2.25");
}

</style>
