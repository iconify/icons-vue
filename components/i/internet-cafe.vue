<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iewobx3ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:internet-cafe" /></template>
<style>
.iewobx3ob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.661 8.896q-.911.75-.911 1.93v8.424q0 1.036.732 1.768t1.768.732h13.5q1.036 0 1.768-.732t.732-1.768v-8.424q0-1.18-.911-1.93l-6.75-5.559q-1.589-1.307-3.178 0zM8.75 10.25h6.5q2.5 0 2.5 2.5v2q0 2.5-2.5 2.5h-2.5v.25h1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T14.5 19h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.75v-.25h-2.5q-2.5 0-2.5-2.5v-2q0-2.5 2.5-2.5");
}

</style>
