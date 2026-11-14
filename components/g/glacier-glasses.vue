<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz2cnxb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glacier-glasses" /></template>
<style>
.iz2cnxb_p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 7.25H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 7.926 1.75 8v5.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.134 0 .26-.047q.126-.046.228-.134l.636-.544q.256 1.012 1.048 1.803Q5.843 16.5 7.5 16.5t2.828-1.172Q11.5 14.157 11.5 12.5V8.75h1v3.75q0 1.657 1.172 2.828Q14.843 16.5 16.5 16.5q3.429 0 3.918-2.939l.594.508q.102.088.228.134t.26.047q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm7.25 1.5h.25v3.119l-.25-.214zm-17.25 0h.25v2.905l-.25.214z");
}

</style>
