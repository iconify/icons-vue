<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_e7jitw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-grid" /></template>
<style>
.yk_e7jitw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2.25h18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q2.926 2.25 3 2.25m.75 6v3h3v-3zm3-1.5v-3h-3v3zm1.5 1.5v3h3v-3zm3-1.5v-3h-3v3zm1.5 1.5v3h3v-3zm3-1.5v-3h-3v3zm1.5 1.5v3h3v-3zm3-1.5v-3h-3v3zm0 6h-3v3h3zm0 4.5h-3v3h3zm-4.5 3v-3h-3v3zm-4.5 0v-3h-3v3zm-4.5 0v-3h-3v3zm-3-4.5h3v-3h-3zm4.5-3v3h3v-3zm4.5 0v3h3v-3z");
}

</style>
