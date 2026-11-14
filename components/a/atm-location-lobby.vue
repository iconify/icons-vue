<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrt4d5bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:atm-location-lobby" /></template>
<style>
.rrt4d5bfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 21.5v-12q0-.09.021-.178q.022-.087.063-.167q.042-.08.101-.148t.132-.12l8.5-6q.095-.067.206-.102T12 2.75t.227.035t.206.102l8.5 6q.073.052.132.12t.101.148t.063.167t.021.178v12q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V9.889L12 4.418L4.25 9.889V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m6.375-11.25q-3.375 0-3.375 3.375v5.25q0 3.375 3.375 3.375h5.75q3.375 0 3.375-3.375v-5.25q0-3.375-3.375-3.375z");
}

</style>
