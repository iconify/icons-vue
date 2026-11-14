<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbjuiacri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:euro-pallet" /></template>
<style>
.jbjuiacri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 7.25H4q-2.25 0-2.25 2.25v1q0 2.25 2.25 2.25h.25v.5H4q-2.25 0-2.25 2.25T4 17.75h.25v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.75h5.5v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.75h5.5v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.75H20q2.25 0 2.25-2.25T20 13.25h-.25v-.5H20q2.25 0 2.25-2.25v-1q0-2.25-2.25-2.25m-8.75 5.5v.5h-5.5v-.5zm7 0v.5h-5.5v-.5z");
}

</style>
