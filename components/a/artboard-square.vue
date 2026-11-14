<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m56cl_blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:artboard-square" /></template>
<style>
.m56cl_blw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2.75H4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014H10q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 2.75 10 2.75m6.875 2.75h-9.75Q3.75 5.5 3.75 8.875v9.75q0 1.398.989 2.386q.988.989 2.386.989h9.75q1.398 0 2.386-.989q.989-.988.989-2.386v-9.75q0-3.375-3.375-3.375");
}

</style>
