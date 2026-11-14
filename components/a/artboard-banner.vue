<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1wbumb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:artboard-banner" /></template>
<style>
.j1wbumb2g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 6H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H9q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9 6m9.875 2.75H5.125q-1.398 0-2.386.989q-.989.988-.989 2.386v1.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-1.75q0-3.375-3.375-3.375");
}

</style>
