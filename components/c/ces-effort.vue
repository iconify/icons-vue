<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8j2sxvaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ces-effort" /></template>
<style>
.u8j2sxvaj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 6.97l1.72 1.719L9.47 4.97q.105-.106.243-.163T10 4.75t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-4.25 4.25q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163L2.97 8.03q-.106-.105-.163-.243T2.75 7.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M6.5 12.5Q3 12.5 3 16t3.5 3.5q3.102 0 3.455-2.75H20.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H9.955Q9.602 12.5 6.5 12.5");
}

</style>
