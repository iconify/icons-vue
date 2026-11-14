<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-wb-zb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:charity-golf-day" /></template>
<style>
.c-wb-zb7z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 16.511V8.916q.759.288 1.585-.043l1.961-.783q1.416-.566 1.416-2.09t-1.416-2.089l-1.96-.784h-.001q-.826-.331-1.585-.043V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8 3v13.511Q3 16.669 3 19q0 2.5 5.75 2.5T14.5 19q0-2.331-5-2.489M18 20.5q-3 0-3-3t3-3t3 3t-3 3");
}

</style>
