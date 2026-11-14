<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njdorq33v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:input-time" /></template>
<style>
.njdorq33v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 5.25H6.875q-2.123 0-3.624 1.501T1.75 10.375v3.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624T17.125 5.25M3.75 12q0-1.553 1.098-2.652Q5.947 8.25 7.5 8.25q3.75 0 3.75 3.75T7.5 15.75T3.75 12m14.75-.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T12.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
