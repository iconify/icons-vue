<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxiavebsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:customer-data-platform" /></template>
<style>
.zxiavebsk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 5q0-2.5 4-2.5q1.535 0 2.654.602Q22.25 3.827 22.25 5v12.5q0 1.173-1.346 1.898Q19.785 20 18.25 20q-4 0-4-2.5zm1.5 8.374V17.5q0 1 2.5 1t2.5-1v-4.273q-1.069.523-2.5.523q-1.551 0-2.5-.376m5-2.124V6.977q-1.069.523-2.5.523q-1.551 0-2.5-.376v4.126q0 1 2.5 1t2.5-1M4 9q0-4 4-4t4 4t-4 4t-4-4m-.421 7.173Q1.75 18.117 1.75 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T3.25 21q0-2.289 1.421-3.798Q6.037 15.75 8 15.75t3.329 1.452Q12.75 18.711 12.75 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.883-1.829-4.827Q10.611 14.25 8 14.25t-4.421 1.923");
}

</style>
