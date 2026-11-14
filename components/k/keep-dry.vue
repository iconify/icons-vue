<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugshs1nge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:keep-dry" /></template>
<style>
.ugshs1nge {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.813 4.813Q3.25 7.376 3.25 11q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7.25v5.75q0 .414-.293.707t-.707.293q-1 0-1-1q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768v-5.75H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.624-2.563-6.187T12 2.25T5.813 4.813");
}

</style>
