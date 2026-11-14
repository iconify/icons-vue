<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrnvyys7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:art-print" /></template>
<style>
.yrnvyys7x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 2.5v2.25H5.125q-3.375 0-3.375 3.375v10.75q0 3.375 3.375 3.375h10.25q3.375 0 3.375-3.375V14.75h2.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H10q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146m9.5 5.625q0-3.375-3.375-3.375H10.75v-1.5h10v10h-2zm-5-.625Q16 7.5 16 9.75v7.5q0 2.25-2.25 2.25h-7q-2.25 0-2.25-2.25v-7.5q0-2.25 2.25-2.25z");
}

</style>
