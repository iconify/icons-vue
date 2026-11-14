<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_-za3bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:body-wrap" /></template>
<style>
.o_-za3bnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.236 8.079Q2.25 9.721 2.25 12t.986 3.921Q4.333 17.75 6 17.75h12.5q3.25 0 3.25-5.75T18.5 6.25H6q-1.667 0-2.764 1.829m8.514-.329v8.5H8.552q.109-.156.212-.329q.986-1.642.986-3.921t-.986-3.921q-.103-.173-.212-.329zm1.5 8.5v-8.5h1.5v8.5zm5.25 0h-2.25v-8.5h2.25q1.75 0 1.75 4.25t-1.75 4.25m-12.49-5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 11.25z");
}

</style>
