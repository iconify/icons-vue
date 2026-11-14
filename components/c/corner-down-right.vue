<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpormvq7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:corner-down-right" /></template>
<style>
.hpormvq7e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 11V4.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.574 3.75 4.5 3.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V11q0 1.76 1.245 3.005T8 15.25h9.689l-3.719 3.72q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l5-5q.106-.105.163-.243t.057-.287q0-.148-.056-.285t-.16-.242l-.004-.003l-5-5q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l3.719 3.72H8q-1.139 0-1.945-.805Q5.25 12.139 5.25 11");
}

</style>
