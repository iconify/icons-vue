<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g9ct0jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:korfball" /></template>
<style>
.s_g9ct0jl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5q0-2.5 5.75-2.5T20.25 5v5q0 2.5-5.75 2.5T8.75 10v-.25h-2v11H9q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 22.25H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 20.75h2.25V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 3.25 6 3.25t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T6.75 4v4.25h2zm1.5 5q0 1 4.25 1t4.25-1V6.902q-1.437.598-4.25.598t-4.25-.598z");
}

</style>
