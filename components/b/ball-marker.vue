<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl4w69bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-marker" /></template>
<style>
.nl4w69bmv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 8q0-2.589 1.831-4.419Q11.911 1.75 14.5 1.75t4.419 1.831T20.75 8t-1.831 4.419q-1.83 1.831-4.419 1.831t-4.419-1.831T8.25 8m-4.328 7.708Q1.75 16.794 1.75 18.5t2.172 2.792q1.916.958 4.578.958t4.578-.958q2.172-1.086 2.172-2.792t-2.172-2.792q-1.916-.958-4.578-.958t-4.578.958M8.51 17.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
