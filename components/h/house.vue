<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktoawib-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:house" /></template>
<style>
.ktoawib-i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.201 4.953l-4.5 3.937Q3.25 10.16 3.25 12.088V16.5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5v-4.412q0-1.928-1.451-3.198l-4.5-3.937q-2.799-2.45-5.598 0M14.5 20.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 20v-4q0-1.75-1.75-1.75T10.25 16v4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 20v-4q0-3.25 3.25-3.25T15.25 16v4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014");
}

</style>
