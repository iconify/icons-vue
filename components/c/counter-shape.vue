<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfkgnxbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:counter-shape" /></template>
<style>
.dfkgnxbop {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 21v-1.936q.213.277.456.541q1.98 2.145 4.794 2.145t4.794-2.145q1.956-2.119 1.956-5.105t-1.956-5.105Q15.314 7.25 12.5 7.25T7.706 9.395q-.243.264-.456.541V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q6.574 1.75 6.5 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.25 21");
}

</style>
