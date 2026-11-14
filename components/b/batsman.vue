<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpj1q6bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:batsman" /></template>
<style>
.hpj1q6bdz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 7.25H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 8v11.5q0 2.75 2.75 2.75h1q2.75 0 2.75-2.75V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 7.25H8.25V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zM13 18.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5");
}

</style>
