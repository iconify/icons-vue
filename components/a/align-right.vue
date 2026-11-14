<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p05fsgbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:align-right" /></template>
<style>
.p05fsgbtp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.75 21.5v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 1.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146M7.125 3.75h8.25q3.375 0 3.375 3.375v.25q0 3.375-3.375 3.375h-8.25q-3.375 0-3.375-3.375v-.25q0-3.375 3.375-3.375m8.25 9.5h-3.25q-3.375 0-3.375 3.375v.25q0 3.375 3.375 3.375h3.25q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375");
}

</style>
