<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuul5zt3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:door-handle" /></template>
<style>
.kuul5zt3j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.746 6.75Q10.623 3.25 7 3.25Q3.25 3.25 3.25 7v10q0 3.75 3.75 3.75T10.75 17v-4.75h7.75q2.75 0 2.75-2.75T18.5 6.75zm.004 4v-2.5h7.75q1.25 0 1.25 1.25t-1.25 1.25zm-3 6.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 17.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 17v-2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 13.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
