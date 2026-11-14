<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuxtd157y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:industrial-network" /></template>
<style>
.yuxtd157y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 6.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H4v3.007q-2.25.121-2.25 2.493v1q0 2.5 2.5 2.5h1q2.5 0 2.5-2.5v-1q0-2.372-2.25-2.493V8.25h5.75v3.007Q9 11.378 9 13.75v1q0 2.5 2.5 2.5h1q1.036 0 1.768-.732T15 14.75v-1q0-1.036-.732-1.768q-.642-.642-1.518-.721V8.25h5.75v3.007q-2.25.121-2.25 2.493v1q0 2.5 2.5 2.5h1q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768q-.642-.642-1.518-.721V8.25h1.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
