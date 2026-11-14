<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8bat3hae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:analog-clock-lesson" /></template>
<style>
.y8bat3hae {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M11.25 6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 5.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.061l3.618 2.035q.13.073.222.191q.092.117.132.261q.04.143.023.292q-.018.148-.091.278t-.191.222t-.261.132t-.292.023t-.278-.091l-4-2.25l-.042-.026q-.079-.051-.142-.12t-.108-.151q-.044-.082-.067-.173T11.25 12z");
}

</style>
