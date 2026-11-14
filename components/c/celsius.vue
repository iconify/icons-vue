<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t25fv4bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:celsius" /></template>
<style>
.t25fv4bht {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.295 16.556q.283-2.152 1.955-3.44V5.5q0-3.25 3.25-3.25t3.25 3.25v7.616q1.672 1.288 1.955 3.44q.311 2.359-1.258 4.147T9.5 22.492q-2.379 0-3.947-1.789t-1.258-4.147M17.5 2.75q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75t-2.75-2.75M10.25 16V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9.5 8.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.75 9v7q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
