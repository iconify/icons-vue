<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnmz5-wmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colonoscopy" /></template>
<style>
.pnmz5-wmm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.431 19.988Q.721 17.994 2.058 16q-1.173-1.75 0-3.5q-1.173-1.75 0-3.5q-1.265-1.887.197-3.773q.131-3.391 3.569-3.475Q7.912.779 10 1.674q2-.857 4 0q2.088-.895 4.176.078q3.438.084 3.569 3.475q1.462 1.886.197 3.773q1.173 1.75 0 3.5q1.173 1.75 0 3.5q1.337 1.994-.373 3.988q-.106.125-.256.193q-.149.069-.313.069h-1.25v-8.604q1-.323 1-1.646q0-1.75-1.75-1.75T17.25 10q0 1.323 1 1.646v8.604H17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-11q0-1.25-1.25-1.25H9q-1.25 0-1.25 1.25v11q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 20.25H3q-.164 0-.313-.069q-.15-.068-.256-.193");
}

</style>
