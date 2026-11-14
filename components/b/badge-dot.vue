<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2qx64s1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:badge-dot" /></template>
<style>
.v2qx64s1n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.701 8.299q-.952-.952-.951-2.298v-.002q-.001-1.346.951-2.298q.952-.953 2.299-.953t2.299.953t.951 2.298q.001 1.347-.951 2.3T18 9.252t-2.299-.953M6 4.25h6.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014H6Q2.75 2.75 2.75 6v12q0 3.25 3.25 3.25h12q3.25 0 3.25-3.25v-6.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V18q0 1.75-1.75 1.75H6q-1.75 0-1.75-1.75V6q0-1.75 1.75-1.75");
}

</style>
