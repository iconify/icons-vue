<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg225db2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand-hierarchy" /></template>
<style>
.dg225db2g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.875 1.75h-1.75q-3.375 0-3.375 3.375v.25q0 3.375 3.375 3.375h.125v2.5H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 12v3.25h-.125q-1.398 0-2.386.989q-.989.988-.989 2.386v.25q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375H6.75v-2.5h10.5v2.5h-.125q-3.375 0-3.375 3.375v.25q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375h-.125V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 11.25h-5.25v-2.5h.125q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375");
}

</style>
