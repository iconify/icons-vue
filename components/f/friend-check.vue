<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="femcxpb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:friend-check" /></template>
<style>
.femcxpb-u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 7.75Q3.5 4 7.25 4T11 7.75T7.25 11.5T3.5 7.75m13.25-3.5q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5t-3.5-3.5M3.355 16.06Q1.75 17.641 1.75 20q0 1.75 1.75 1.75H11q1.75 0 1.75-1.75q0-2.359-1.605-3.94Q9.563 14.5 7.25 14.5t-3.895 1.56M17 18.689l-1.22-1.219q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T14.5 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113l1.75 1.75q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4-4q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
