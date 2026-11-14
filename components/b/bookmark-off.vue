<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh0e8hb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bookmark-off" /></template>
<style>
.nh0e8hb7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 15.922L6.154 3.326q.041-.044.085-.087q.988-.989 2.386-.989h6.75q1.398 0 2.386.989q.989.988.989 2.386zM4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m10.52 16.38q1.131.848 2.378.406L5.25 8.078v9.172q0 1.622 1.451 2.348t2.749-.248l1.425-1.069q1.125-.844 2.25 0z");
}

</style>
