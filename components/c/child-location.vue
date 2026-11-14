<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb1jc5bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:child-location" /></template>
<style>
.lb1jc5bwm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.47 22.03q-.436-.435-1.42-1.376Q3.25 14.158 3.25 10q0-3.624 2.563-6.187T12 1.25t6.187 2.563T20.75 10q0 4.158-6.8 10.654q-.984.941-1.42 1.376q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094M15 7.5q0-3-3-3t-3 3t3 3t3-3M7.75 15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.25-4.25-3.25T7.75 15");
}

</style>
