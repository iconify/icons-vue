<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucgdqgbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dry-mouth" /></template>
<style>
.ucgdqgbiv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.469 16.641L8.385 5.556q1.322-1.698 3.067-3.568q.017-.019.036-.036q.109-.102.249-.154t.289-.048q.149.006.285.067t.237.171Q19.75 9.704 19.75 14.5q0 1.129-.281 2.141M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M12 22.25q3.093 0 5.314-2.108L6.085 8.914Q4.25 12.079 4.25 14.5q0 3.21 2.27 5.48T12 22.25");
}

</style>
