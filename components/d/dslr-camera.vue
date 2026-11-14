<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf81kkexy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dslr-camera" /></template>
<style>
.wf81kkexy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.005 6.25H4.5q-1.139 0-1.945.805Q1.75 7.861 1.75 9v10q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-2.505l-1.306-3.045q-.043-.102-.114-.186q-.07-.085-.162-.145q-.092-.061-.197-.092Q15.11 2.75 15 2.75h-4q-.11 0-.216.032q-.105.031-.197.092q-.092.06-.162.145t-.114.186zM6.25 18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 18v-8q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146zM13 11.75q2.25 0 2.25 2.25T13 16.25T10.75 14T13 11.75");
}

</style>
