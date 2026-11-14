<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stzt3fgac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dive-flag" /></template>
<style>
.stzt3fgac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 5.98V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.574 2.25 4.5 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.75 2.926 3.75 3v18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.25 21v-5.125q.75.375 1.875.375h9.75q1.122 0 1.871-.373zm15 6.895q0 1.177-.411 1.944L5.254 4.123q.749-.373 1.871-.373h9.75q3.375 0 3.375 3.375z");
}

</style>
