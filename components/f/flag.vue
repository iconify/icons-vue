<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ein7eoe1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flag" /></template>
<style>
.ein7eoe1d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 3.377V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q5.074 2.25 5 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 3v18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.75 21v-6.877q.436.127 1 .127h9.441q1.358 0 2.013-1.189t-.07-2.336l-.91-1.441q-.337-.534 0-1.068l.91-1.44q.725-1.148.07-2.337T16.191 3.25H6.75q-.564 0-1 .127");
}

</style>
