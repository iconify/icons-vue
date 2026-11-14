<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj2h_rbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lampshade" /></template>
<style>
.aj2h_rbqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.197 2.25h7.606q1.71 0 2.33 1.594l2.139 5.5q.478 1.229-.267 2.318q-.744 1.088-2.063 1.088H12.75v7.5h3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.75v-7.5H6.058q-1.319 0-2.063-1.088t-.267-2.318l2.139-5.5q.62-1.594 2.33-1.594");
}

</style>
