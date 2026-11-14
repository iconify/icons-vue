<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icbjxac0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aarti-plate" /></template>
<style>
.icbjxac0i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m10.836-5.969q-.052-.065-.117-.117q-.117-.093-.26-.134t-.292-.025q-.148.016-.279.088q-.13.072-.224.188Q9.75 8.112 9.75 10.438q0 .758.164 1.312H7.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 2.175 1.538 3.712Q9.825 17.75 12 17.75t3.712-1.538q1.538-1.537 1.538-3.712q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.414q.164-.554.164-1.312q0-2.326-1.664-4.407");
}

</style>
