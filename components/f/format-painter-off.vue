<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6wqpxbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:format-painter-off" /></template>
<style>
.o6wqpxbjf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 11.25h-4.922l1.5 1.5H19q1.75 0 1.75-1.75V7q0-1.75-1.75-1.75h-1.769q-.116-1.158-.97-2.011q-.988-.989-2.386-.989h-7.75q-.488 0-.926.12l7.379 7.38h1.297q3.182 0 3.364-3H19q.25 0 .25.25v4q0 .25-.25.25M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m2.892 6.78L2.75 5.579v.796q0 3.375 3.375 3.375zm7.328 9.75v-2.422l-3.199-3.199Q9.75 14.289 9.75 16v3.5q0 2.25 2.25 2.25t2.25-2.25");
}

</style>
