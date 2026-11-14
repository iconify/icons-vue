<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8d5kwbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:breathalyser" /></template>
<style>
.e8d5kwbzp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 1.75q2.5 0 2.5 2.5v1.5q0 .641-.281 1.166q1.278.334 2.28 1.335q1.501 1.501 1.501 3.624v5.25q0 2.123-1.501 3.624t-3.624 1.501h-1.75q-2.123 0-3.624-1.501T6.25 17.125v-5.25q0-2.123 1.501-3.624q.966-.966 2.19-1.31q-.191-.5-.191-1.191v-1.5q0-2.5 2.5-2.5M11.5 9.5Q9 9.5 9 12v.5q0 1.036.732 1.768T11.5 15H13q1.036 0 1.768-.732T15.5 12.5V12q0-2.5-2.5-2.5zm.76 7.75h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.5 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
