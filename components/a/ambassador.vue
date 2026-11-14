<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7qq-xb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ambassador" /></template>
<style>
.c7qq-xb0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 7.75V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-19q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T17 1.75h4.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014zm0-1.5h3v-3h-3zM5.318 5.318Q4 6.636 4 8.5t1.318 3.182T8.5 13t3.182-1.318T13 8.5t-1.318-3.182T8.5 4T5.318 5.318M1.75 20.5q0-6 6.75-6q6.25 0 6.25 6q0 1.75-1.75 1.75H3.5q-1.75 0-1.75-1.75");
}

</style>
