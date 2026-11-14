<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdm6bkb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:influencer-search" /></template>
<style>
.sdm6bkb3v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.391 4.141Q4 5.532 4 7.5t1.391 3.359T8.75 12.25t3.359-1.391T13.5 7.5t-1.391-3.359T8.75 2.75T5.391 4.141M13.25 17.5q0-1.163.543-2.101q-.071-.059-.145-.116q-1.971-1.533-4.898-1.533t-4.898 1.533Q1.75 16.918 1.75 19.5v1q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H15q.178 0 .337-.08q-.447-.27-.842-.665Q13.25 19.26 13.25 17.5m4.25-3q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
