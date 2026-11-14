<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6sgdbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kefir" /></template>
<style>
.oj6sgdbne {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 2.75h-3.5q-2.5 0-2.5 2.5q0 1.118.5 1.736V7.5q0 .536-1.585 1.329Q4.25 10.036 4.25 11.5v8q0 2.75 2.75 2.75h10q2.75 0 2.75-2.75v-8q0-1.464-2.415-2.671Q15.75 8.036 15.75 7.5V7q0-.106-.029-.208q.529-.661.529-1.542q0-1.036-.732-1.768T13.75 2.75m6 10.75q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 12.75h14q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
