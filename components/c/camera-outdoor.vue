<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktjkx04rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-outdoor" /></template>
<style>
.ktjkx04rn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2h15.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 2 6 2m13.5 11.75q2.75 0 2.75-4.5t-2.75-4.5H8.75q-1.864 0-3.182 1.318T4.25 9.25t1.318 3.182T8.75 13.75h2v3.75h-4.5v-1q0-2.25-2.25-2.25T1.75 16.5V20q0 2.25 2.25 2.25T6.25 20v-1h5.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.5zm-2.259-7.5q-.491 1.098-.491 3t.491 3H8.75q-3 0-3-3t3-3z");
}

</style>
