<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay_awcwva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-jersey" /></template>
<style>
.ay_awcwva {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 1.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V5q0 .978-1.076 2.27Q4.25 8.978 4.25 10.5v10q0 1.75 1.75 1.75h12q1.75 0 1.75-1.75v-10q0-1.522-1.424-3.23Q17.25 5.978 17.25 5V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 1.75-1.75 1.75T10.25 2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q9.574 1.75 9.5 1.75zm.75 11.75q0-3.75 3.75-3.75t3.75 3.75T12 17.25T8.25 13.5");
}

</style>
