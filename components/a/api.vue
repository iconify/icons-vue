<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdqa6bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:api" /></template>
<style>
.dqdqa6bkd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 6.25q1.45 0 2.475 1.025q.652.652.889 1.475H10.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.75h1.5V9.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.834q.458-2.5 3.416-2.5q1.45 0 2.475 1.025T22.25 9.75v4.5q0 3.5-3.5 3.5q-2.958 0-3.416-2.5H13.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.75h-1.5v1.75q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8.666q-.458 2.5-3.416 2.5q-3.5 0-3.5-3.5v-4.5q0-3.5 3.5-3.5m9 5.75v1.75h1v-3.5h-1zm-4.5 0v-1.75h-1v3.5h1z");
}

</style>
