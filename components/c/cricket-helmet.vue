<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7dux7pnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cricket-helmet" /></template>
<style>
.d7dux7pnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 18.75v-4.5q0-4.209 2.85-7.004Q8.399 4.5 12.5 4.5q7.309 0 8.737 7.61v.002q.013.067.013.136v.002q0 2.929-1.163 4.938q-1.208 2.086-3.156 2.29q-.089.022-.181.022q-.037 0-.074-.004q-.087.004-.176.004h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m14.75-.912q2.067-.739 2.235-4.838H17.5zM16 13h-2.25v5H16z");
}

</style>
