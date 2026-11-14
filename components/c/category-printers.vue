<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0rwukexv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-printers" /></template>
<style>
.j0rwukexv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.505 10.495Q19.35 9.339 17.75 9.256V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 2.75H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v5.756q-1.6.083-2.755 1.239Q2.25 11.74 2.25 13.5v1q0 1.76 1.245 3.005q1.155 1.156 2.755 1.239V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.756q1.6-.083 2.755-1.239Q21.75 16.26 21.75 14.5v-1q0-1.76-1.245-3.005M16.25 9.25h-8.5v-5h8.5z");
}

</style>
