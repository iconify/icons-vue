<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noxig504b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gum" /></template>
<style>
.noxig504b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8v12q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8q0-3.75-3.75-3.75q-2.073 0-3 1.146q-.927-1.146-3-1.146T9 5.396Q8.073 4.25 6 4.25Q2.25 4.25 2.25 8m1.5 0q0-2.25 2.25-2.25T8.25 8v6.216Q7.073 15.5 6 15.5t-2.25-1.284zM12 15.5q-1.073 0-2.25-1.284V8q0-2.25 2.25-2.25T14.25 8v6.216Q13.073 15.5 12 15.5m3.75-1.284V8q0-2.25 2.25-2.25T20.25 8v6.216Q19.073 15.5 18 15.5t-2.25-1.284");
}

</style>
