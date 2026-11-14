<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xalhhg5cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:innings-scoreboard" /></template>
<style>
.xalhhg5cf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v6q0 1.76-1.245 3.005T18 17.25h-.25V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.25 21v-3.75h-8.5V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 21v-3.75H6q-1.76 0-3.005-1.245T1.75 13V7q0-1.76 1.245-3.005T6 2.75m2 3.5q-2.75 0-2.75 3.75T8 13.75T10.75 10T8 6.25M13.25 10q0 3.75 2.75 3.75T18.75 10T16 6.25T13.25 10");
}

</style>
