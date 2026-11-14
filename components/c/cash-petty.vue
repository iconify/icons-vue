<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6bzoe_fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cash-petty" /></template>
<style>
.z6bzoe_fq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 8.25q0-2.5 2.5-2.5q.623 0 1.137.265q.549-.265 1.363-.265q1.036 0 1.768.732t.732 1.768t-.732 1.768q-.127.127-.264.232H19q.087 0 .172.02t.163.059q.079.039.146.095t.119.126q2.65 3.533 2.65 6.95q0 4.75-4.75 4.75h-11q-4.75 0-4.75-4.75q0-3.417 2.65-6.95q.052-.07.119-.126t.146-.095t.163-.059t.172-.02h4.014q-.764-.618-.764-2m11.75 5H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 13.25");
}

</style>
