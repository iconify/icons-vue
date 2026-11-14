<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqolleb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dashboard-on-tv" /></template>
<style>
.hqolleb0w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25H6q-1.76 0-3.005 1.245T1.75 6.5V13q0 1.76 1.245 3.005T6 17.25h5.25v3H7.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.75 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.75v-3H18q1.76 0 3.005-1.245T22.25 13V6.5q0-1.76-1.245-3.005T18 2.25m-10.75 3h1.5q2.5 0 2.5 2.5v4q0 2.5-2.5 2.5h-1.5q-2.5 0-2.5-2.5v-4q0-2.5 2.5-2.5m10.125 0q1.875 0 1.875 1.875T17.375 9h-2.75Q12.75 9 12.75 7.125t1.875-1.875zm-2.75 5.25h2.75q1.875 0 1.875 1.875t-1.875 1.875h-2.75q-1.875 0-1.875-1.875t1.875-1.875");
}

</style>
