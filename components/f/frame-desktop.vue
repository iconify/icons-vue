<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1gdavduy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:frame-desktop" /></template>
<style>
.s1gdavduy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 3.25h13.75q3.375 0 3.375 3.375v6.75q0 3.375-3.375 3.375H12.75v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 20q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.25h3.25v-2.5H5.125q-3.375 0-3.375-3.375v-6.75q0-3.375 3.375-3.375");
}

</style>
