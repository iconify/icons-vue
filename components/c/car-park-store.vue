<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieiivvbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-park-store" /></template>
<style>
.ieiivvbvx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25h12.5q2.5 0 2.5 2.5v.5q0 1.581-1 2.162V12.5h-1.5V7.75H4.75v11h2V12.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6.25H14v1.5H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V7.412q-1-.581-1-2.162v-.5q0-2.5 2.5-2.5m3.5 16.5h2.5v-5.5h-2.5zm7.75 3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-7q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75q3 0 3 3t-3 3h-2v1.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m2.75-4q1.5 0 1.5-1.5t-1.5-1.5h-2v3zM18 16.5h.75v.5H18z");
}

</style>
