<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbcxpqblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lanterns-string" /></template>
<style>
.tbcxpqblw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.75h2.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.75v3.087q2 .502 2 3.913q0 4-2.75 4t-2.75-4q0-3.411 2-3.913V4.25h-5.5v8.587q2 .502 2 3.913q0 4-2.75 4t-2.75-4q0-3.411 2-3.913V4.25h-5.5v3.087q2 .502 2 3.913q0 4-2.75 4t-2.75-4q0-3.411 2-3.913V4.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 3.574 1.75 3.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014z");
}

</style>
