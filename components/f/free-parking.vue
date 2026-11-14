<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov7szzbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:free-parking" /></template>
<style>
.ov7szzbgc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.413 2.25H5.625q-1.398 0-2.386.989q-.989.988-.989 2.386v4.788q0 1.398.989 2.386l6.875 6.875q2.386 2.386 4.772 0l4.788-4.788q2.386-2.386 0-4.772l-6.875-6.875q-.988-.989-2.386-.989M9.75 13.5V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H13q3 0 3 3t-3 3h-1.75v2.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146zm1.5-.75H13q1.5 0 1.5-1.5T13 9.75h-1.75z");
}

</style>
