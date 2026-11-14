<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zap0_dzdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ac-compressor" /></template>
<style>
.zap0_dzdv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 5.541Q10.815 5.25 12 5.25t2.25.291V5q0-2.75 2.75-2.75h2.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H17q-1.25 0-1.25 1.25v1.125q1.121.579 2.084 1.541q2.416 2.417 2.416 5.834t-2.416 5.834T12 21.75t-5.834-2.416Q3.75 16.917 3.75 13.5t2.416-5.834q.963-.962 2.084-1.541V5q0-1.25-1.25-1.25H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.75 3.074 3.75 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H7q2.75 0 2.75 2.75zM8.5 13.5Q8.5 10 12 10t3.5 3.5T12 17t-3.5-3.5");
}

</style>
