<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rom5f1ukz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loop-band" /></template>
<style>
.rom5f1ukz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 8.5V5q0-.074-.014-.146t-.043-.141q-.028-.068-.069-.129q-.041-.062-.093-.114t-.113-.093t-.13-.069q-.068-.029-.14-.043q-.073-.015-.146-.015q4.18 0 7.16 2.196Q22.25 8.722 22.25 12t-3.088 5.554Q16.182 19.75 12 19.75t-7.162-2.196Q1.75 15.278 1.75 12t3.088-5.554q2.98-2.196 7.16-2.196q-.073 0-.146.015q-.072.014-.14.043t-.13.069q-.061.041-.113.093t-.093.114q-.041.061-.069.129q-.028.069-.043.141T11.25 5v3.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
