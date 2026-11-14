<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxd_bh9mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:archimedes" /></template>
<style>
.oxd_bh9mb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 19v-8.25h3.5v2.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-2.5h3.5V19q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25m14.5-9.75h-3.5v-.5q0-1.036-.732-1.768T13.25 6.25h-2.5q-2.5 0-2.5 2.5v.5h-3.5V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.074 3.25 4 3.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.25 3.926 3.25 4v15q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 3.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T19.25 4z");
}

</style>
