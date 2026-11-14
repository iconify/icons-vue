<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc8ewgprf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-kennel-run" /></template>
<style>
.wc8ewgprf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.29 3.575L4.04 9.434q-.79.741-.79 1.824v7.992q0 1.036.732 1.768t1.768.732h12.5q1.036 0 1.768-.732t.732-1.768v-7.992q0-1.083-.79-1.824l-6.25-5.859q-1.71-1.603-3.42 0M15 21.75q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 21v-5q0-2.25-2.25-2.25T9.75 16v5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 21v-5q0-3.75 3.75-3.75T15.75 16v5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014");
}

</style>
