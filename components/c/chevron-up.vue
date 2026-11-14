<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhc7qub3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-up" /></template>
<style>
.fhc7qub3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.97 14.47l6.5-6.5q.105-.106.243-.163T12 7.75t.287.057t.243.163l6.5 6.5q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094L12 9.561L6.03 15.53q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T4.75 15t.057-.287t.163-.243");
}

</style>
