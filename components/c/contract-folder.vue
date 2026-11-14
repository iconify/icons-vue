<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5dy00bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contract-folder" /></template>
<style>
.e5dy00bkk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 9.25V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h4.5q.149 0 .287.057t.243.163l3.75 3.75q.106.105.163.243t.057.287v3.06q2 .345 2 2.69v7q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75v-9q0-1.139.805-1.945q.806-.805 1.945-.805h2q.149 0 .287.057t.243.163l1.781 1.78zm7.189-3.75L16.5 4.311V5.5zM15 3.25h-3v6h6.75V7h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T15 6.25z");
}

</style>
