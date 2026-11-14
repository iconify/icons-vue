<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2k1vzbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beamed-sixteenths" /></template>
<style>
.a2k1vzbor {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 4v11.905Q8.378 15.5 7 15.5q-3.75 0-3.75 3t3.75 3t3.75-3V8.25h8.5v7.655Q18.378 15.5 17 15.5q-3.75 0-3.75 3t3.75 3t3.75-3V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 3.25H10q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9.25 4m10 2.75h-8.5v-2h8.5z");
}

</style>
