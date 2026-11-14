<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6aw1s2wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boom-arm" /></template>
<style>
.t6aw1s2wp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 2.75h15q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.25h.02q1.845 0 2.206 1.809l.4 2q.209 1.044-.466 1.868q-.675.823-1.74.823h-2.34q-1.065 0-1.74-.823q-.675-.824-.466-1.868l.4-2q.361-1.809 2.206-1.809h.02v-2.5h-10v13.515q4 .17 4 2.235q0 2.25-4.75 2.25T2.25 20q0-2.065 4-2.235V4.25H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.75 3.574 2.75 3.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
