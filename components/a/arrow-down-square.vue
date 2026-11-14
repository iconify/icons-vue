<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5g7ftbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-down-square" /></template>
<style>
.e5g7ftbxw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.625 21.25q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.75q0 2.848-2.014 4.861t-4.861 2.014zm2.905-4.22l4-4q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 11.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-2.72 2.719V7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 6.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7.189L8.53 11.97q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 11.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l4 4q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16z");
}

</style>
