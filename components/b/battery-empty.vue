<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdhbqqb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-empty" /></template>
<style>
.zdhbqqb1t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.625 6.25h-7.75q-2.123 0-3.624 1.501T1.75 11.375v1.25q0 2.123 1.501 3.624t3.624 1.501h7.75q2.123 0 3.624-1.501t1.501-3.624v-1.25q0-2.123-1.501-3.624T14.625 6.25m7.625 4.25v3q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
