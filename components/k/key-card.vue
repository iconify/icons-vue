<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cib1z7bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:key-card" /></template>
<style>
.cib1z7bpn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 4.25H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T17.125 4.25M5 12q0-3 3-3q1.243 0 2.121.879q.601.6.791 1.371H17.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.25v1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T15.5 15t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.5h-3.838q-.19.771-.791 1.371Q9.243 15 8 15q-3 0-3-3");
}

</style>
