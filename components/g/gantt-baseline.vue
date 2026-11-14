<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kudlgq4wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gantt-baseline" /></template>
<style>
.kudlgq4wy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 3v18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 21V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T4.25 3M14.5 4.25H9q-3.25 0-3.25 3.25T9 10.75h5.5q3.25 0 3.25-3.25T14.5 4.25m-1.5 8.5h5.5q1.346 0 2.298.952T21.75 16t-.952 2.298t-2.298.952H13q-3.25 0-3.25-3.25T13 12.75");
}

</style>
