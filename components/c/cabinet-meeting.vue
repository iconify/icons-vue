<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z25_qchsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cabinet-meeting" /></template>
<style>
.z25_qchsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 8q0-3.75 3.75-3.75T15.75 8T12 11.75T8.25 8m-6.5 3q0-2.75 2.75-2.75T7.25 11T4.5 13.75T1.75 11M19.5 8.25q-2.75 0-2.75 2.75t2.75 2.75T22.25 11T19.5 8.25m-13 11.5h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19q0-4 2.75-4q1.134 0 1.971.616Q7.873 13 12 13t5.529 2.616Q18.366 15 19.5 15q2.75 0 2.75 4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014zm11.724-1.5h2.493q-.171-1.75-1.217-1.75q-.857 0-1.426.653q.108.517.15 1.097m-1.51 0Q16.336 14.5 12 14.5t-4.714 3.75zm-10.938 0q.042-.58.15-1.097Q5.357 16.5 4.5 16.5q-1.046 0-1.217 1.75z");
}

</style>
