<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkeykxbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:inbox-search" /></template>
<style>
.hkeykxbyr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 2.75Q8 2.75 8 6.25t3.5 3.5q1.059 0 1.892-.547l1.078 1.077q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-1.077-1.078Q15 7.309 15 6.25q0-1.45-1.025-2.475T11.5 2.75M3 11.25h5q.097 0 .191.025q.094.024.179.072t.154.116t.119.151l1.282 2.136h4.15l1.282-2.136q.05-.083.119-.151q.07-.068.154-.116q.085-.048.179-.072q.094-.025.191-.025h5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75v-6q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 11.25");
}

</style>
