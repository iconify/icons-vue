<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dww0s2bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lab-label-printer" /></template>
<style>
.dww0s2bwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 7.256V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 2.75 7 2.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.756q1.6.083 2.755 1.239Q21.75 9.74 21.75 11.5v2q0 1.76-1.245 3.005q-1.155 1.156-2.755 1.239V18q0 .149-.057.287t-.163.243l-2.5 2.5q-.105.106-.243.163t-.287.057H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.756q-1.6-.083-2.755-1.239Q2.25 15.26 2.25 13.5v-2q0-1.76 1.245-3.005Q4.65 7.339 6.25 7.256m1.5 10.494v2h6.439l2-2zm8.5-10.5v-3h-8.5v3z");
}

</style>
