<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i70vhudej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-rattle-music" /></template>
<style>
.i70vhudej {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.081 3.581Q2.25 5.411 2.25 8t1.831 4.419q1.559 1.56 3.669 1.791v1.085Q5 15.648 5 18.75q0 3.5 3.5 3.5t3.5-3.5q0-3.102-2.75-3.455V14.21q2.11-.231 3.669-1.791Q14.75 10.589 14.75 8t-1.831-4.419T8.5 1.75T4.081 3.581M18.25 15.5q0 2.75-2.75 2.75t-2.75-2.75t2.75-2.75q.719 0 1.25.188V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.227 0 .416.126q.276.184.892.53Q21.75 5.561 21.75 8q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21 8.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T20.25 8q0-1.496-2-2.684zM6.5 18.75q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
