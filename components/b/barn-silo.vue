<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovjco4bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barn-silo" /></template>
<style>
.ovjco4bhv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 7v14q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7q.001-1.498 1.5-1.498t1.5 1.499V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.999q-.002-2.997-3-2.997T16.25 7M2.539 13.04L4.35 9.82q.369-.656 1.059-.958l2.919-1.277q.932-.407 1.853.022l2.699 1.259q.655.306 1.01.936l1.821 3.238q.289.513.289 1.102v5.108q0 2.25-2.25 2.25H10.5q1-.5 1-2V17q0-2.25-2.25-2.25h-1.5Q5.5 14.75 5.5 17v2.5q0 1.5 1 2h-2q-2.25 0-2.25-2.25v-5.107q0-.589.289-1.103");
}

</style>
