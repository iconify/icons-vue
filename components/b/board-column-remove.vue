<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhcnbbgjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:board-column-remove" /></template>
<style>
.hhcnbbgjr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.629 2.629q.878-.879 2.121-.879q3 0 3 3v14.5q0 3-3 3t-3-3V4.75q0-1.243.879-2.121M15 13.25v-8.5q0-3-3-3t-3 3v8.5q0 3 3 3t3-3m1.25-8.5q0-3 3-3t3 3v4.5q0 3-3 3t-3-3zM15 17.25h6q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
