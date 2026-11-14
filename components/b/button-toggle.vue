<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwwx0cs2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:button-toggle" /></template>
<style>
.vwwx0cs2n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 5.25H6.875q-2.123 0-3.624 1.501T1.75 10.375v3.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624T17.125 5.25m-8.875 3h1.5q3.75 0 3.75 3.75t-3.75 3.75h-1.5Q4.5 15.75 4.5 12q0-1.553 1.098-2.652Q6.697 8.25 8.25 8.25M19.5 12q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H15.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
