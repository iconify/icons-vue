<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yce6sbo4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dark-web-monitor" /></template>
<style>
.yce6sbo4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.75H6.875q-2.123 0-3.624 1.501T1.75 7.875v4.25q0 2.123 1.501 3.624t3.624 1.501h4.375v2.5H8q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 19.75h-3.25v-2.5h4.375q2.123 0 3.624-1.501t1.501-3.624v-4.25q0-2.123-1.501-3.624T17.125 2.75M12.001 5.5q1.863 0 3.181 1.318T16.5 10t-1.318 3.182T12 14.5t-3.182-1.318T7.5 10t1.318-3.182T11.999 5.5z");
}

</style>
