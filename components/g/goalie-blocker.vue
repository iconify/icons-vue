<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0sdc5rvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goalie-blocker" /></template>
<style>
.t0sdc5rvn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.123 0 3.624 1.501t1.501 3.624v4.75q0 2.123-1.501 3.624q-1.002 1.001-2.28 1.335q.281.525.281 1.166v1q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15.5 18h-7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v-1q0-.691.191-1.191q-1.224-.344-2.19-1.31q-1.501-1.501-1.501-3.624v-4.75q0-2.123 1.501-3.624T9.375 1.75m-1.625 17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v1q0 1.036-.732 1.768t-1.768.732h-3.5q-1.036 0-1.768-.732T7.75 19.75z");
}

</style>
