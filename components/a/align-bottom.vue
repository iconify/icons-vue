<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuus_ybjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:align-bottom" /></template>
<style>
.tuus_ybjj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.125 3.75h.25q3.375 0 3.375 3.375v8.25q0 3.375-3.375 3.375h-.25q-3.375 0-3.375-3.375v-8.25q0-3.375 3.375-3.375m9.75 5h-.25q-3.375 0-3.375 3.375v3.25q0 3.375 3.375 3.375h.25q3.375 0 3.375-3.375v-3.25q0-3.375-3.375-3.375m4.625 11.5h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
