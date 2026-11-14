<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbtp59z2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basil-sprig" /></template>
<style>
.rbtp59z2s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 6.25q0 .099-.004.196Q15.747 5.75 18 5.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 5.893-6 6.23V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 21v-6.27q-6-.337-6-6.23q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 7.75q3.568 0 5.25 1.746V9.36q-1.5-1.284-1.5-3.11q0-2 1.8-3.35q.048-.036.102-.064t.111-.048t.117-.028q.06-.01.12-.01t.12.01t.117.028q.058.02.111.048q.054.028.102.064q1.8 1.35 1.8 3.35");
}

</style>
