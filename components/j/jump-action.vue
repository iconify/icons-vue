<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="safep5sfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jump-action" /></template>
<style>
.safep5sfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.591 3.531q-.659-.66-1.591-.66t-1.591.66L5.884 8.055q-.747.746-.343 1.721T7 10.75h.5q.75 0 .75.75v4q0 2.25 2.25 2.25h3q2.25 0 2.25-2.25v-4q0-.75.75-.75h.499q1.056.001 1.46-.974t-.343-1.72zM20.5 20.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
