<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q71n6ipjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:council-tax-bill" /></template>
<style>
.q71n6ipjf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 2.75 2.75 2.75h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v5.368q-2.319-2.038-4.638.125l-2.249 2.099l-.001.001q-1.112 1.038-1.112 2.559v1.598q0 1.209.417 2H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m13.03 6.22l-5.999-6q.105.106.162.243q.057.138.057.287v4q0 1.25 1.25 1.25h4q.149 0 .287.057t.243.163m-5.815 9.037v-.001l2.25-2.099q1.535-1.431 3.07-.001l2.25 2.101q.715.667.715 1.645v1.598q0 2.25-2.25 2.25h-4.5q-2.25 0-2.25-2.25v-1.598q0-.978.715-1.645m1.024 1.097q-.239.222-.239.548v1.598q0 .75.75.75h4.5q.75 0 .75-.75v-1.598q0-.326-.239-.549l-2.25-2.099q-.511-.477-1.022-.001zm1.011.765v.881h3.5v-.881L18 17.236z");
}

</style>
