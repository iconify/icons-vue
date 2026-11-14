<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_pe25db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-eyepiece" /></template>
<style>
.ey_pe25db {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2.75h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m5.625 2.75h-4.25q-2.123 0-3.624 1.501T1.75 10.625v4.75q0 2.123 1.501 3.624T6.875 20.5h4.25q2.123 0 3.624-1.501t1.501-3.624V13.25h.56q.345 2 2.69 2q2.75 0 2.75-2.75v-4q0-2.75-2.75-2.75q-2.345 0-2.69 2H15.5q-.058 0-.116.009q-.274-.397-.635-.758Q13.248 5.5 11.125 5.5M5.25 13q0-3.75 3.75-3.75T12.75 13T9 16.75T5.25 13m11.5-3.75v2.5h-.5v-1.125q0-.724-.174-1.375z");
}

</style>
