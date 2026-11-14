<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdikt07kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flag-penalty-number" /></template>
<style>
.zdikt07kw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 15.75v5.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-19q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.75H19q1.75 0 1.75 1.75v9q0 1.75-1.75 1.75zm0-1.5H19q.25 0 .25-.25V5q0-.25-.25-.25H5.25zm5.25-8H14q.932 0 1.591.659T16.25 8.5v2q0 .932-.659 1.591T14 12.75h-3.5q-2.25 0-2.25-2.25v-2q0-2.25 2.25-2.25");
}

</style>
