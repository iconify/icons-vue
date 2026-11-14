<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xasjeinsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brew-airlock" /></template>
<style>
.xasjeinsd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 6.25V5.5q0-2.75 2.75-2.75t2.75 2.75q0 1.25 1.25 1.25t1.25-1.25v-2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T20 2.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2q0 2.75-2.75 2.75T15.25 5.5q0-1.25-1.25-1.25T12.75 5.5v.75h.75q2 0 2 2q0 1.225-.75 1.699v.551q0 .412 1.89 1.254q3.61 1.607 3.61 3.746v4q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75v-4q0-2.139 3.61-3.746q1.89-.842 1.89-1.254v-.551Q8.5 9.475 8.5 8.25q0-2 2-2z");
}

</style>
